<div align="center">

<h1>KoppisOS</h1>

<p>
  Clean • Fast • Minimal Android Experience
</p>

<p>
  <img src="https://img.shields.io/badge/Android-17.0-green">
  <img src="https://img.shields.io/badge/Architecture-ARM64-blue">
  <img src="https://img.shields.io/badge/GSI-A%2FB-orange">
  <img src="https://img.shields.io/badge/Status-Beta-brightgreen">
</p>

</div>

<hr>

<h2>About</h2>

<p>
  <strong>KoppisOS</strong> is a lightweight Android operating system designed to provide a clean, responsive, and junk-free experience.
  Built on Android 17.0 with a Pixel-inspired approach to usability and system simplicity.
</p>

<p>
  Developed as a Generic System Image (GSI) for broad compatibility across modern ARM64 A/B Android devices.
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
  <tr>
    <td><strong>Security Patch</strong></td>
    <td>2026 Release Base</td>
  </tr>
</table>

<hr>

<h2>Features</h2>

<ul>
  <li>Minimal system footprint</li>
  <li>Fast boot and smooth performance</li>
  <li>Pixel-inspired clean interface</li>
  <li>No unnecessary bundled software</li>
  <li>Broad ARM64 A/B compatibility</li>
</ul>

<hr>

<h2>Supported Devices</h2>

<table>
  <tr>
    <th>Requirement</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>ARM64 Architecture</td>
    <td>Required</td>
  </tr>
  <tr>
    <td>A/B Partition Layout</td>
    <td>Required</td>
  </tr>
  <tr>
    <td>Unlocked Bootloader</td>
    <td>Required</td>
  </tr>
  <tr>
    <td>Dynamic Partitions</td>
    <td>Recommended</td>
  </tr>
</table>

<hr>

<h2>Download</h2>

<p>
  <a href="https://github.com/Chucny/KoppisOS/releases">Download Latest Release</a>
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
  <li>First startup may take 5–10 minutes</li>
  <li>Initial optimization process is normal</li>
  <li>Do not force reboot during first initialization</li>
</ul>

<hr>

<h2>Known Issues</h2>

<ul>
  <li>No known critical issues in current release</li>
  <li>Device-specific vendor limitations may apply</li>
</ul>

<hr>

<h2>Important Warning</h2>

<table>
  <tr>
    <td>
      <strong>Always back up your original system and vbmeta before flashing.</strong><br><br>
      Flashing custom firmware can permanently affect your device if done incorrectly.
    </td>
  </tr>
</table>

<hr>

<h2>Release Status</h2>

<p>
  Stable public release for testing and daily use on supported devices.
</p>

<hr>

<h2>Support</h2>

<ul>
  <li>Releases are published via GitHub Releases</li>
  <li>Future builds may improve compatibility and performance</li>
</ul>

<hr>

<div align="center">
<strong>Copyright &copy; Chucny 2026</strong>
</div>
