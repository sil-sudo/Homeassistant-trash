# Chechlist in order

1. Install HASS OS on SD card for RPI and get it online

2. Create admxxx account and log in

3. Update to latest

4. Enable Backups

5. Install HACS

6. Install Plugins
    - Studio Code Server
    - TasmoAdmin
    - CEC Scanner
    - ESP Home
    - File Editor
    - Terminal
    - music assistant (custom repo)
      
7. Install and configure cloudflared (custom repositories) https://github.com/brenner-tobias/addon-cloudflared
    - In user settings enable advanced mode
    - Enable External Access and set external URL
    - Set 172.30.x.x as trusted proxy
    - Enter API key in addon
    - Disable ipv6
      
8. Install HACS Plugins
    - iOS Themes - Dark Mode and light mode
    - Bambulab Integration
    - mini graph card
    - button card
    - card mod
    - Home Assistant Swipe
    - Stack in Card
    - template entity row
      
9. Configure and adopt devices

10. Configure ESPhome and flash NSPanel https://github.com/Blackymas/NSPanel_HA_Blueprint?tab=readme-ov-file#-documentation--resources
    - Use Documentation to compile ESP32 Image (use only lowercase for name)
    - Flash ESP32 Image to NSpanel
    - Adopt ESP32
    - Update Nextion
    - Configure Blueprint
