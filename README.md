## Mosquito Sensor using Arduino as a listening device (UT-DIY Diagnostic Lab)

#### Working design using ATMEGA2560 : ATMEGA-Mosquito-Sensor-v1.ino

#### Initial attempt at using Arduino Zero (32 bit microcontroller) : Sketches under AZ-* folders

#### Goals:
   * Construct Arduino based mosquito listening device. Microphone with preamplifier connected to Arduino Zero analog in port (Analog to digital convertor input). Digital samples from ADC stored in SD Card in WAVE format.
   * Analyze WAV files using FFT spectrograms to identify type and sex of mosquitos

#### Challenges:
   * There are many example designs on the web to record audio onto an SD card. However they use the Arduino Uno with a different kind of microcontroller compared to the Arduino Zero.
   * Lot of power supply noise, eliminated by having a separate power supply for the microphone amplifier
   * Microphone hiss, reduced by audio processing program (Audacity)
   
#### ATMEGA-Arduino Listening Device
![pic](/images/device.jpg)

#### Sample Spectrogram
![pic](/images/spectrogram.png)

