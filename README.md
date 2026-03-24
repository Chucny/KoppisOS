<h1>KoppisOS</h1>

<p>
  A clean, lightweight Android operating system designed for speed, simplicity, and a junk-free user experience.
</p>

<p>
  Built on <strong>Android 17.0</strong> and optimized for <strong>ARM64 A/B devices</strong> as a Generic System Image (GSI).
</p>

<hr>

<h2>Release Information</h2>

<table>
  <tr>
    <td><strong>Version</strong></td>
    <td>1.0</td>
  </tr>
  <tr>
    <td><strong>Build ID</strong></td>
    <td><code>KoppisOS_1.0_arm64</code></td>
  </tr>
  <tr>
    <td><strong>Android Base</strong></td>
    <td>Android 17.0</td>
  </tr>
  <tr>
    <td><strong>Architecture</strong></td>
    <td>ARM64</td>
  </tr>
  <tr>
    <td><strong>Partition Type</strong></td>
    <td>A/B Devices</td>
  </tr>
  <tr>
    <td><strong>Format</strong></td>
    <td>GSI</td>
  </tr>
</table>

<hr>

<h2>Features</h2>

<ul>
  <li>Minimal and clean Android experience</li>
  <li>Fast performance without unnecessary system apps</li>
  <li>Pixel-inspired usability</li>
  <li>Wide compatibility across modern devices</li>
</ul>

<hr>

<h2>Requirements</h2>

<ul>
  <li>Unlocked bootloader</li>
  <li>Physical Android device</li>
  <li>ADB and Fastboot installed</li>
  <li>Latest KoppisOS release downloaded</li>
</ul>

<hr>

<h2>Download</h2>

<p>
  <a href="https://github.com/Chucny/KoppisOS/releases">Download latest release</a>
</p>

<hr>

<h2>Installation</h2>

<pre><code>adb reboot bootloader
fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img
fastboot reboot fastboot
fastboot flash system system.img
fastboot reboot</code></pre>

<hr>

<h2>First Boot</h2>

<ul>
  <li>Initial boot may take 5–10 minutes</li>
  <li>Boot delay during first startup is normal</li>
  <li>Do not interrupt setup during first initialization</li>
</ul>

<hr>

<h2>Important Notice</h2>

<p>
  Always back up your original system image and vbmeta before flashing.
</p>

<p>
  Flashing custom firmware may permanently affect device stability if performed incorrectly.
</p>

<hr>

<h2>Support</h2>

<p>
  Release updates and future builds are published through GitHub Releases.
</p>

<hr>

<p><strong>Copyright &copy; Chucny 2026</strong></p>
