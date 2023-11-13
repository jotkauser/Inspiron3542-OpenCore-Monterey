# macOS Monterey for Dell Inspiron 3542

Hi, this is EFI for Inspiron 3542 to run macOS
**EVERYTHING HIGHER THAN MONTEREY WILL NOT WORK WITHOUT ANY PROBLEMS**

# Specs
| Component | Name |
|:--- |:---|
| CPU | **Intel** i5-4210u |
| RAM | **8GB** DDR3 |
| iGPU | **Intel** HD 4400 |
| dGPU | **NVIDIA** GeForce 820M (OFF) | 
| SSD | **512 GB SSD** |
| WIFI/BT | **AR9565** |
| Audio | **Realtek** ALC255 |
| Ethernet | **Realtek** RTL8111 |
<strong>Note:</strong> The WiFi/BT card needs to be replaced with a **compatible** one in order to get full wireless functionality
# Wireless
I can't test bluetooth as i bought Intel card that lacks bluetooth functionality. But in order to get bluetooth you can use ASUS-BT400 dongle
I used Intel® Centrino® Advanced-N 6205 card to get wifi
# Status
- ### **Fully working**
  - Built-in display
  - Ethernet
  - Audio 
  - Wi-Fi (after card replacement)
  - Camera
  - Ethernet
  - Keyboard
  - SSD and DVD drive
  - HDMI
- ### **Partially working**
    - Touch-pad (works iffy [clicks not registered sometimes])
- ### **Untested**
  - AirDrop
  - Bluetooth (should work with a WiFi+BT intel card)
  - FaceTime
  - Card reader (its on usb)
- ### **Not working**
  - dGPU
# INSTALLATION GUIDE
1. Put EFI on your USB drive
2. Get macOS installer media (can be found on Dortania OpenCore guide)
3. Install
4. Enjoy
**Report any problems in issues tab!**
