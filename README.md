# KoppisOS
KoppisOS is an Android operative system, with the goal to make a clean, fast OS without any junk. Uses the newest Android 17.0 and works on litterally all new Android phones! Google Pixel like experience with the newest Android 17.0 OS! Needed: an unlocked bootloader and PHYSICAL android device.<br>
Android 17.0 OS. Works on all arm64 A/B devices as a GSI.<br>
ID: <code>KoppisOS_1.0_arm64</code>
<h3>How to use</h3>
<code>adb reboot bootloader</code><br><code>fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img</code><br>
<code>fastboot reboot fastboot</code><br>
<code>fastboot flash system system.img</code><br>
<code>fastboot reboot</code><br>Note: First boot can take about 5-10min. Do not think it's a bootloop unless it is clearly looping.<br>
<strong>Always back up your original system and vbmeta before flashing.</strong><br><br><strong>Copyright &copy; Chucny 2026</strong>
