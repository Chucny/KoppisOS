<img src="https://www.gstatic.com/devrel-devsite/prod/v8b8ef181e1dc913802015af34f7ea88ee446e0cb5daec5c977ac4c46a7a372bd/android/images/lockup.png"></img><br>
<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/d/d7/Android_robot.svg" width="80">

<h1 style="margin-bottom:4px;">KoppisOS</h1>

<p style="font-size:16px;">
  Android 17.0 Generic System Image
</p>

<p>
  <img src="https://img.shields.io/badge/Android-17.0-34A853">
  <img src="https://img.shields.io/badge/Status-Beta-4285F4">
  <img src="https://img.shields.io/badge/Architecture-ARM64-FBBC05">
  <img src="https://img.shields.io/badge/GSI-A%2FB-EA4335">
</p>

</div>

<br>

<hr>

<h2>Platform Release</h2>

<p>
KoppisOS is a lightweight Android operating system designed for a clean, fast and junk-free experience.
Built on Android 17.0 and optimized for modern ARM64 A/B devices as a Generic System Image.
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
<td>A/B</td>
</tr>
<tr>
<td><strong>Format</strong></td>
<td>GSI</td>
</tr>
</table>

<hr>

<h2>Download</h2>

<p>
<a href="https://github.com/Chucny/KoppisOS/releases">Download latest release</a>
</p>

<hr>

<h2>Device Requirements</h2>

<ul>
<li>Unlocked bootloader</li>
<li>Physical Android device</li>
<li>ADB installed</li>
<li>Fastboot installed</li>
<li>vbmeta support</li>
</ul>

<hr>

<h2>Flash a system image</h2>

<pre><code>adb reboot bootloader
fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img
fastboot reboot fastboot
fastboot flash system system.img
fastboot reboot</code></pre>

<hr>

<h2>First boot</h2>

<ul>
<li>First startup may take 5–10 minutes</li>
<li>Initial system optimization is normal</li>
<li>Do not interrupt first boot</li>
</ul>

<hr>

<h2>Important Notice</h2>

<table>
<tr>
<td>
<strong>Always back up your original system and vbmeta before flashing.</strong><br><br>
Flashing custom firmware may permanently affect your device if performed incorrectly.
</td>
</tr>
</table>

<hr>

<h2>Compatibility</h2>

<ul>
<li>ARM64 devices</li>
<li>A/B partition layout</li>
<li>Modern Android phones</li>
</ul>

<hr>

<h2>Release Status</h2>

<p>
Beta public release for supported devices.
</p>

<hr>

<div align="center">

<strong>Copyright &copy; Chucny 2026</strong>

</div>
