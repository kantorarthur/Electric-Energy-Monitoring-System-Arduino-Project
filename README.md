<img width="615" height="527" alt="system picture" src="https://github.com/user-attachments/assets/c808ea7f-efb5-4d01-859a-86fc87941977" />
<html>
<body>
<!--StartFragment--><h2 class="text-text-100 mt-3 -mb-1 text-[1.375rem] font-bold">Electric Energy Monitoring System using Arduino</h2>
<p class="font-claude-response-body break-words whitespace-normal">An Arduino-based single-phase electrical monitoring system that measures voltage, current, power, and energy consumption in real time, with built-in overvoltage/undervoltage protection.</p>
<h3 class="text-text-100 mt-3 -mb-1 text-[1.125rem] font-bold">Overview</h3>
<p class="font-claude-response-body break-words whitespace-normal">This project implements a low-cost smart meter capable of reading AC electrical parameters and automatically cutting power through a relay when abnormal voltage conditions are detected. It is designed for educational use, home experimentation, and basic smart home applications.</p>
<h3 class="text-text-100 mt-3 -mb-1 text-[1.125rem] font-bold">Features</h3>
<ul class="[li_&amp;]:mb-0 [li_&amp;]:mt-1 [li_&amp;]:gap-1 [&amp;:not(:last-child)_ul]:pb-1 [&amp;:not(:last-child)_ol]:pb-1 list-disc flex flex-col gap-1 pl-8 mb-3">
<li class="font-claude-response-body whitespace-normal break-words pl-2"><strong>Real-time measurement</strong> of AC voltage (ZMPT101B) and AC current (SCT-013)</li>
<li class="font-claude-response-body whitespace-normal break-words pl-2"><strong>Automatic calculation</strong> of active power (W) and cumulative energy consumption (kWh)</li>
<li class="font-claude-response-body whitespace-normal break-words pl-2"><strong>LCD I2C 16x2 display</strong> alternating between voltage/current/power and energy/protection status</li>
<li class="font-claude-response-body whitespace-normal break-words pl-2"><strong>Relay-based protection</strong> that disconnects the load when voltage goes below 190 V or above 250 V</li>
<li class="font-claude-response-body whitespace-normal break-words pl-2"><strong>EEPROM persistence</strong> — energy data is saved every 5 seconds and retained across reboots</li>
<li class="font-claude-response-body whitespace-normal break-words pl-2"><strong>Software safety limits</strong>: current capped at 10 A, voltage validated between 90–300 V</li>
</ul>

</div>
<h3 class="text-text-100 mt-3 -mb-1 text-[1.125rem] font-bold">Libraries Used</h3>
<ul class="[li_&amp;]:mb-0 [li_&amp;]:mt-1 [li_&amp;]:gap-1 [&amp;:not(:last-child)_ul]:pb-1 [&amp;:not(:last-child)_ol]:pb-1 list-disc flex flex-col gap-1 pl-8 mb-3">
<li class="font-claude-response-body whitespace-normal break-words pl-2"><strong>EmonLib</strong> — RMS current and voltage calculation</li>
</ul>
<h3 class="text-text-100 mt-3 -mb-1 text-[1.125rem] font-bold">Known Limitations</h3>
<ul class="[li_&amp;]:mb-0 [li_&amp;]:mt-1 [li_&amp;]:gap-1 [&amp;:not(:last-child)_ul]:pb-1 [&amp;:not(:last-child)_ol]:pb-1 list-disc flex flex-col gap-1 pl-8 mb-3">
<li class="font-claude-response-body whitespace-normal break-words pl-2">Not suitable for high-power appliances (washing machines, AC units, boilers) due to sensor range limits</li>
<li class="font-claude-response-body whitespace-normal break-words pl-2">Simplified power calculation (no explicit power factor / cos φ)</li>
<li class="font-claude-response-body whitespace-normal break-words pl-2">Susceptible to electromagnetic noise from the relay and unshielded cables</li>
<li class="font-claude-response-body whitespace-normal break-words pl-2">General-purpose relay with limited lifespan under inductive loads</li>
</ul>
<h3 class="text-text-100 mt-3 -mb-1 text-[1.125rem] font-bold">Author</h3>
<p class="font-claude-response-body break-words whitespace-normal">Kantor Arthur — Technical University of Cluj-Napoca, Computer Science.</p><!--EndFragment-->
</body>
</html>


https://github.com/user-attachments/assets/d13a6b95-e693-48cd-a719-02f8e1b572bd
