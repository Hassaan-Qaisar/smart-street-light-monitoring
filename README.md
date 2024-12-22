# project-remote-light-monitoring
<p>This project is a <strong>street monitoring system</strong> implemented using an ESP32 microcontroller. It utilizes the <strong>Blynk IoT platform</strong> for remote monitoring and control, integrates an LCD display for local output, and uses sensors and LEDs to manage and monitor street lighting based on ambient light levels.</p>

<h2>Features</h2>
<ul>
    <li><strong>Automatic and Manual Modes:</strong>
        <ul>
            <li>Automatic adjustment of LED brightness based on ambient light levels.</li>
            <li>Manual control of LEDs through the Blynk dashboard.</li>
        </ul>
    </li>
    <li><strong>Blynk Integration:</strong>
        <ul>
            <li>Monitor and control the system remotely via the Blynk mobile app or dashboard.</li>
            <li>Real-time sensor readings and control states displayed on the Blynk terminal.</li>
        </ul>
    </li>
    <li><strong>LCD Display:</strong>
        <ul>
            <li>Provides local feedback on system mode and light intensity.</li>
        </ul>
    </li>
    <li><strong>Physical Buttons:</strong>
        <ul>
            <li>Switch between automatic and manual modes.</li>
            <li>Control LEDs manually in manual mode.</li>
        </ul>
    </li>
</ul>

<h2>Hardware Requirements</h2>
<ul>
    <li><strong>ESP32 Microcontroller</strong></li>
    <li><strong>WiFi Network</strong></li>
    <li><strong>16x2 LCD Display</strong></li>
    <li><strong>LDR Sensor</strong> (Light-Dependent Resistor)</li>
    <li><strong>LEDs</strong> (For simulating street lights)</li>
    <li><strong>Push Buttons</strong></li>
    <li><strong>Resistors and Wires</strong></li>
</ul>

<h2>Software Requirements</h2>
<ul>
    <li><strong>Arduino IDE</strong></li>
    <li>Required Libraries:
        <ul>
            <li><code>WiFi.h</code></li>
            <li><code>WiFiClient.h</code></li>
            <li><code>BlynkSimpleEsp32.h</code></li>
            <li><code>LiquidCrystal.h</code></li>
        </ul>
    </li>
</ul>

<h2>Setup Instructions</h2>
<ol>
    <li><strong>Install Libraries</strong>
        <p>Ensure the following libraries are installed in your Arduino IDE:</p>
        <ul>
            <li><code>WiFi</code></li>
            <li><code>BlynkSimpleEsp32</code></li>
            <li><code>LiquidCrystal</code></li>
        </ul>
    </li>
    <li><strong>Configure Blynk</strong>
        <ul>
            <li>Create a new template in the Blynk platform.</li>
            <li>Replace the following placeholders in the code with your Blynk template information:</li>
        </ul>
        <pre><code>#define BLYNK_TEMPLATE_ID "Your_Template_ID"

    
