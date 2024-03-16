# Blink-Command-ESP32
This was the first Activity Set in my first workshop conducted by my university as a part of my subject, Engineering Explorations. I have given a step by step guide in this repo as to how I was able to blink the built-in led on ESP32 Microcontroller, and so can you!

<img width="561" alt="image" src="https://github.com/Dhruti-Avadhani/Blink-Command-ESP32/assets/155796125/46a71ba5-5a53-4b82-9c34-21fe4d006685">
<br>

<h1>Prerequisites</h1><br>
<p>1. You need to have Arduino IDE installed and running on your computer device</p><br>
<p>2. You also need to have 2101 drivers installed on your device</p><br>

<br>

<h1>Installing ESP-32 in Arduino IDE</h1>
<br>
<h2>Step 1 : </h2><br>
<p>1. Go to "File" and select "Preferences"</p>
<br>
<p>2. Enter the following into “Additional Board Manager URLs” field </p>
<p>https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json</p>
<br>
<p>3. Click "OK" to save changes</p>

<br>
<h2>Step 2 : </h2><br>
<p>1. Open "Boards Manager" by navigating to Tools > Board >Boards Manager</p><br>
<p>2. Search for ESP32 and install the “ESP32 by Espressif Systems“</p><br>
<p>3. Once the installation is done, restart your Arduino IDE</p><br>

<h2>Step 3 : </h2><br>
<p>1. Once you reopen Arduino IDE, navigate to Tools > Board and select ESP32 board</p><br>
<p>2. Choose "ESP32 DEVKIT VI - DOIT" board to work with</p><br>

<h2>Step 4 : </h2><br>
<p>1. Now we can start implementing the blink command.</p><br>
<p>2. Navigate to Files > Examples > Blink, or you can also use the code from the ino file attached in this repo</p>
<p>3. Connect your ESP32 to your computer using a USB to micro USB cable and select the required port to upload your file to the board. If your IDE is unable to detect the port, then you probably do not have the 210x drivers insalled or working. Make sure that you first install the necessary drivers and then proceed</p><br>
<p>4. Once you have detected your port and the board has been selected, upload your code into the board</p><br>
<p>5. Once the upload is done, you will see the builtin LED on the board blinking</p><br>

<h1>210X Drivers Installation</h1><br>
<p>1. Install the Universal Windows 210x Driver from https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads if you are using a windows machine.</p><br>
<p>2. Extract all the files and update settings in your device manager and you are good to go!</p>


