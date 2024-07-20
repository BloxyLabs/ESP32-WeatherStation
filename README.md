# ESP32-WeatherStation

Check also our [YouTube](https://www.youtube.com/@bloxylabs "YouTube") channel for instructions and other related information.
If you had fun with the projects, please consider buying us a [cup of coffee](https://www.buymeacoffee.com/bloxylabs "cupofcoffee") ☕.

Execute the following steps to upload the code to your ESP32
<br>
<br>
**Step 1:** Connect the Oled screen to your ESP32 <br>
You can find the instruction how to connect the oled screen to your ESP32 in the related video on our [YouTube](https://youtu.be/cilyIH6OYY8 "YouTube") channel.  
<table>
<thead>
  <tr>
    <th>I2C OLED</th>
    <th>ESP32 pin</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>VCC</td>
    <td>Vin</td>
  </tr>
  <tr>
    <td>GND</td>
    <td>GND</td>
  </tr>
  <tr>
    <td>SCL</td>
    <td>22</td>
  </tr>
  <tr>
    <td>SDA</td>
    <td>21</td>
  </tr>
</tbody>
</table>


**Step 2:** Create a OpenWeather API and get your location code <br>
Go to the [OpenWeather](https://openweathermap.org "OpenWeather") website. Create a acoount and retrieve you API key from the user menu. Then search for the weather at your location. When the weather at your location is retrieved, just copy the code from your address bar. You need your api key and location code in step 4.

**Step 3:** Install the IDE libraries <br>
Install the following libraries in Arduino IDE:

- ArduinoJson by Benoit Blanchon
- Adafruit GFX Library by Adafruit
- Adafruit SSD1306 by Adafruit
- NTPClient by Fabrice Weinberg or NTPClient_Generic by Fabrice Weinberg

**Step 4:** Adjust the code <br>
Enter your api key, location code, WiFi credentials and timezone in the code. Read the comments in the code or view our YouTube video for more information on this step.

**Step 5:** Upload the code to the ESP32

First check the following prerequisites

- Did you enter the following link in the preferences of the file menu in the field "Additional board manager URLs" => <br>
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json

- Did you install ESP32 by Espressif Systems in the tools menu => Boards Manager

- Did you select the right ESP32 in the tools menu => boards => ESP32

- Did you connect your ESP32 to your computer and selected the right COM port from the tools menu => port
<br>
Now you are ready to verify and upload the code ;)


**Have fun!!**
