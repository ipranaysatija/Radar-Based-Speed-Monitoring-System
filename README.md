# Radar Based Speed Measurment System
This project involves the development of a radar system leveraging the Doppler effect to accurately measure the speed of moving vehicles. The system emits a continuous microwave signal towards the target vehicle and receives the reflected signal. By analyzing the frequency shift between the transmitted and reflected signals, the speed of the vehicle is calculated. The data is then uploaded to the server and can be accessed through the local website.
<p align="center">
  <img src="https://github.com/user-attachments/assets/0047bef1-f741-4480-a9f4-ecb6210c86f1" alt="OPS234 Radar" height="500">
</p>
<p align="center">
  OPS243 Radar
</p>


## Components
**Hardware:** A Doppler radar module, microcontroller for signal processing, and a display unit for real-time speed visualization.

**Software:** Custom algorithms to process frequency shifts and translate them into precise speed measurements.
## Doppler Effect Concept
The Doppler Effect is a phenomenon where the frequency of a wave changes based on the relative motion between the wave source and an observer. If the source and observer move closer together, the observed frequency increases (a shift towards higher frequency). Conversely, if they move apart, the observed frequency decreases (a shift towards lower frequency).

For example:

When an ambulance passes by, the siren's pitch is higher as it approaches and lower as it moves away.

<p align="center">
  <img src="https://github.com/user-attachments/assets/81d7020b-d103-4514-9ad1-65eefe27bd1f" alt="OPS234 Radar" height="200">
</p>

## Application in Speed Measurement
In the context of radar speed measurement:

Transmission of Waves: The radar emits a continuous wave (microwave or radio wave) at a specific frequency.
Reflection: The wave strikes a moving vehicle and reflects back to the radar.
Frequency Shift: The motion of the vehicle causes a shift in the reflected wave's frequency due to the Doppler effect.
Approaching Vehicle: Reflected frequency is higher than the transmitted frequency.
Receding Vehicle: Reflected frequency is lower than the transmitted frequency.
Speed Calculation:
The radar system measures the difference between the transmitted and reflected frequencies (Δf).

Using the Doppler shift formula:
<p align="center">
  <img src="https://github.com/user-attachments/assets/9a476a25-28bc-4e65-b30e-38fdd95e805c" alt="OPS234 Radar" height="100">
</p>

​v: Speed of the vehicle

c: Speed of light (constant)

ft: Transmitted frequency

Δf: Frequency shift

## Project Flow

<p align="center">
  <img src="https://github.com/user-attachments/assets/ac7cff65-5d71-429b-af72-a6b93fdd038b" alt="OPS234 Radar" height="500">
</p>

## Live Speed Detection

<p align="center">
  <img src="https://github.com/user-attachments/assets/a4aa04e0-1e4a-4bc8-9725-cc78146c72b9" alt="OPS234 Radar" height="500">
</p>
<p align="center">
  **Live speed detection and Updation on the server**
</p>


<p align="center">
   <img src="https://github.com/user-attachments/assets/ee7ae25f-21fe-4395-9618-d1a9e76d2847" alt="OPS234 Radar" height="500">
</p>

<p align="center">
  **Data can be reviewed on the site**
</p>




## Future Scope

Integrating a camera with Doppler radar systems can transform them into advanced traffic management tools. Key enhancements include:

**1. Automated Speed Enforcement:** Identify vehicles exceeding speed limits and issue penalties using number plate recognition.

**2. Real-Time Monitoring:** Detect stolen vehicles and manage traffic congestion efficiently.

**3. Data Analytics:** Gather insights for urban planning and monitor vehicle trends.

**4. Smart City Integration:** Enable IoT connectivity and AI-based traffic predictions.

**5. Legal and Regulatory Uses:** Streamline toll collection, insurance claims, and accident investigations.

This integration enhances functionality, making radar systems more effective for traffic safety and smart city initiatives.

<p align="center">
   <img src="https://github.com/user-attachments/assets/4e564670-61c2-417d-9377-3c7129382916" alt="OPS234 Radar" height="300">
   <img src="https://github.com/user-attachments/assets/2d08de6d-ad10-42da-a7e0-5d5a566748d5" alt="OPS234 Radar" height="300">
</p>

<p align="center">
   **Setting Up Camera Module**
</p>

## Installation
Creating Workspace
```bash
  cd /Desktop
  mkdir workspace
  
```
Cloning The Repository
```bash
  cd workspace
  git clone <Repo URL>
```
Test Runing the Python file
```bash
  python3 final.py
```
## Setting up Boot Launch

Making the file executable
```bash
  sudo chmod +x ~/Desktop/workspace/final.py
```
Putting the comand in bashrc
```bash
  sudo gedit ~/.bashrc
```
add the following line at the end of the file
```bash
  python3 final.py
```
now finalize the setup by
```bash
  source ~/.bashrc
```


## Acknowledgements

 - [Doppler Effect Concept](https://www.scienceabc.com/pure-sciences/ambulance-police-siren-sound-different-passes.html)
 - [Seting up Raspberryi Pi](https://www.raspberrypi.com/documentation/computers/getting-started.html)
 - [Launch On Boot](https://help.ubuntu.com/stable/ubuntu-help/startup-applications.html.en)

## Documentation

[Link To Website](https://radar-speed-kgcv.vercel.app/)

[Link To Drive](https://drive.google.com/drive/folders/11kEGkJQ02AlQVz_A3B6SeS6CdDjEDEry?usp=drive_link)

[Link To PPTX](unavailable)
