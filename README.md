<img width="133" height="49" alt="Screenshot 2026-10-30 172157" src="https://github.com/user-attachments/assets/d5ea2b2f-ee26-4d55-8dc9-92126e604390" />
<img width="482" height="443" alt="Screenshot 2026-11-04 220231" src="https://github.com/user-attachments/assets/f02edefd-8f71-4245-85c8-acc36ea97e11" />
<img width="448" height="350" alt="Screenshot 2026-11-08 133554" src="https://github.com/user-attachments/assets/7bf23d8f-c2fd-4091-acb8-a146464b8068" />
<img width="641" height="434" alt="Screenshot 2026-11-07 200838" src="https://github.com/user-attachments/assets/21aa84dc-d174-4a6a-ad97-b9c9a6710517" />
<img width="508" height="337" alt="Screenshot 2026-11-08 133608" src="https://github.com/user-attachments/assets/1f0808ff-1226-43c1-bc2a-53bf0bd20dd2" />
<img width="959" height="500" alt="Screenshot 2026-11-11 194245" src="https://github.com/user-attachments/assets/e0b8b4be-f188-4d2b-a007-14193e489b6d" />
<img width="332" height="217" alt="Screenshot 2026-11-11 193405" src="https://github.com/user-attachments/assets/8b23cbd1-50b0-4f8a-8e55-394ad9eca690" />
<img width="427" height="266" alt="Screenshot 2026-11-11 193351" src="https://github.com/user-attachments/assets/9d7c10b1-bac6-4b4f-bb2e-708f0ae6932e" />
<img width="378" height="240" alt="Screenshot 2026-11-11 193343" src="https://github.com/user-attachments/assets/f82039f4-3de1-49a9-a06f-872059a4483c" />
# AI Robot Head – Custom-Built AI Robotic Companion

A custom-built AI robotic companion featuring a Raspberry Pi 5 with 16GB of RAM, a touchscreen, camera, microphone array, speakers, and a motorized neck.

# Full Parts List

## Main Components

### 1. Raspberry Pi 5 – 16GB RAM (Seeed Studio Starter Kit)
- **Price:** $379.80
- **Quantity:** 1
- **Purpose:** This is the brain of the robot. It will run the AI chatbot, application, camera tracking, microphone processing, and other features. I originally planned to buy the Raspberry Pi by itself, but the 16GB version was no longer showing up on Amazon at the price I found. I switched to a starter kit that includes a fan, which also saves me from buying a separate cooler.
- **Amazon:** https://www.amazon.com/Seeed-Studio-Raspberry-Pi-Starter/dp/B0GD58SJFK

### 2. ELECROW 7-inch 1024×600 Touchscreen
- **Price:** $53.99
- **Quantity:** 1
- **Purpose:** This screen will be used as the robot's face. It will display the chatbot interface and allow the robot to show expressions and information.
- **Amazon:** https://www.amazon.com/ELECROW-Raspberry-Touchscreen-Capacitive-1024x600/dp/B08FMNDDSL

### 3. MMlove 170° USB Camera (OV2710)
- **Price:** $58.99
- **Quantity:** 1
- **Purpose:** This is the robot's camera. It will be used to see and track the user so the robot can follow them by moving its head.
- **Amazon:** https://www.amazon.com/MMlove-Camera-Webcam-170degree-fisheye/dp/B0GVXND5H4

### 4. ReSpeaker XMOS XVF3800 4-Microphone Array
- **Price:** $69.90
- **Quantity:** 1
- **Purpose:** This is the robot's microphone system. It has four microphones and is designed to capture voices from different directions, helping the robot hear the user.
- **Amazon:** https://www.amazon.com/gp/aw/d/B0GVJ5YQ58

### 5. FUNLOGY 14W Stereo PC Speakers
- **Price:** $21.99
- **Quantity:** 1
- **Purpose:** These speakers will provide audio output for the AI chatbot so the robot can speak clearly and loudly enough to be heard.
- **Amazon:** https://www.amazon.com/FUNLOGY-Speaker-Speakers-Powered-Consoles/dp/B0DTYTZGBN

## Motors and Movement

### 6. Smraza Waterproof 270° Servo Motors
- **Price:** $39.99
- **Quantity:** 1 pack (2 motors)
- **Purpose:** These two motors will control the robot's neck movement. One will rotate the head, while the other will move it up and down so it can nod and look around.
- **Amazon:** https://www.amazon.com/dp/B0CX1GZC98

### 7. PCA9685 Servo Controller (HUAREW)
- **Price:** $12.99
- **Quantity:** 1
- **Purpose:** This board will control the servo motors. It connects to the Raspberry Pi and allows the application to send movement commands to the motors.
- **Amazon:** https://www.amazon.com/HUAREW-PCA9685-Interface-Compatible-Raspberry/dp/B0CRV3MK14

### 8. SHNITPWR Adjustable Servo Power Supply
- **Price:** $24.99
- **Quantity:** 1
- **Purpose:** This power supply will provide adjustable voltage and power to the servo motors through the servo controller.
- **Amazon:** https://www.amazon.com/dp/B08N4FB7MF

## Cables and Electrical Components

### 9. ELEGOO 120-Piece Dupont Jumper Wire Kit
- **Price:** $6.98
- **Quantity:** 1 kit
- **Purpose:** These wires will connect the Raspberry Pi to the PCA9685 servo controller and other electronic components. They carry control signals between the boards.
- **Amazon:** https://www.amazon.com/dp/B01EV70C78

### 10. 18-AWG DC Power-Wire Kit
- **Price:** $10.39
- **Quantity:** 1 kit
- **Purpose:** These thicker wires will connect the servo power supply to the servo controller and carry power to the motors.
- **Amazon:** https://www.amazon.com/dp/B072BXB2Y8

### 11. One Beat Power Strip
- **Price:** $12.99
- **Quantity:** 1
- **Purpose:** This will be installed inside the robot's base to provide power to the components that need to be plugged into a wall outlet and keep the power connections organized.
- **Amazon:** https://www.amazon.com/dp/B0B1DKN9HG

### 12. RasTech Raspberry Pi 5 GaN PD 27W USB-C Power Supply
- **Price:** $12.34
- **Quantity:** 1
- **Purpose:** This power adapter will provide power to the Raspberry Pi 5.
- **Amazon:** https://www.amazon.com/RasTech-Power-Supply-Raspberry-Adapter/dp/B0CLV6WB4L

### 13. SanDisk Extreme 128GB microSD Card + Adapter
- **Price:** $41.99
- **Quantity:** 1
- **Purpose:** This card will store Raspberry Pi OS, the robot's application, and other files needed to run the robot.
- **Amazon:** https://www.amazon.com/SANDISK-Extreme-microSD-Adapter-Speeds/dp/B0G8LLXFJH

## 3D Printing Materials – Bambu Lab

### 14. Bambu Lab PETG Basic Filament
- **Price:** $14.44 per roll
- **Quantity:** 4 rolls
- **Total:** $57.76
- **Purpose:** PETG will be used to 3D print the robot's body and mechanical components. I chose PETG because it is suitable for strong functional parts, including gears and structural components. I also want to use multiple colors.
- **Bambu Lab:** https://us.store.bambulab.com/products/petg-basic

### 15. Bambu Lab Support for PLA/PETG
- **Price:** $20.99
- **Quantity:** 1 roll
- **Purpose:** This filament will be used as support material during 3D printing. It helps support difficult geometries and makes removing supports easier, improving the finish of printed parts.
- **Bambu Lab:** https://us.store.bambulab.com/products/support-for-pla-petg

# Total Estimated Project Cost

## Amazon Purchases

| Description | Price |
|---|---:|
| Amazon parts subtotal | $747.33 |
| Estimated Amazon sales tax (8%) | $59.79 |
| Amazon shipping | Free |
| **Amazon total** | **$807.12** |

## Bambu Lab Purchases

| Description | Price |
|---|---:|
| PETG filament (4 rolls) | $57.76 |
| Support filament (1 roll) | $20.99 |
| Bambu Lab subtotal | $78.75 |
| Bambu Lab tax (assumed $0.00) | $0.00 |
| Bambu Lab shipping | Not included |
| **Bambu Lab total** | **$78.75** |

## Grand Total

| Description | Price |
|---|---:|
| Amazon total including estimated tax | $807.12 |
| Bambu Lab total | $78.75 |
| **Estimated Grand Total** | **$885.87** |

*Tax is estimated at 8% for Amazon purchases only. Bambu Lab tax is currently assumed to be $0.00, as requested, and should be confirmed at checkout. Filament shipping, if applicable, is not included.*

# About the Project

The 3D model is complete, but it is still difficult to print. When I start building the robot, I'll modify the model to make all the parts fully printable and easier to assemble.

This is an AI robotic companion and chatbot. It will be able to rotate its head and nod up and down using two servo motors. It will also have a camera to track the user and a microphone array so you can talk with it.

I've developed a full application for the robot that is designed to run on a Raspberry Pi 5 with 16GB of RAM.

I know that a cheaper setup with 8GB of RAM might be possible, but I estimate that I would have to remove around 75% of the planned features. That wouldn't make the project worth the approximately $500 cost to me. However, if someone wants an 8GB version, I'm willing to consider making one.

I've made the application very easy to install. Currently, it can be installed using a simple `.exe` file.

When I start building the physical robot, I plan to adapt the application to run directly on Raspberry Pi OS (Linux), rather than relying on the Windows executable. This should make it run more smoothly and integrate better with the robot's hardware.

I haven't been able to test the application on a Raspberry Pi yet because I don't currently own one. All my development and testing so far have been done on my Windows PC.

Below are the application file and videos demonstrating the AI application running on my computer.

# Application and Demonstrations

### Windows Application (.exe)

https://drive.google.com/file/d/1h9VeBtCXhQ4OoPYfxNRKdbChb2cyTcSq/view?usp=sharing

### Videos Showing the AI Application Running on My PC

**Video 1:**

https://drive.google.com/file/d/11tZIuAtOSYqX6bwp0hpNuKTanBxRtTHR/view?usp=sharing

**Video 2:**

https://drive.google.com/file/d/1Jr9HSe4ddXIZgk4nltNuLcAXCt6QMBxz/view?usp=sharing

**Video 3:**

https://drive.google.com/file/d/1fODqtLviIr7q9icY4muSxNgAIR2JrqG8/view?usp=sharing

### MakerWorld Project

https://makerworld.com/en/models/3593933-ai-robot-head-chatbot
