# ZipRipper - A CMD script to crack password protected ZIP, RAR, 7z, and PDF files, using JohnTheRipper

<p align="center">
<img src="https://github.com/illsk1lls/ZipRipper/blob/main/.resources/zipripper.png?raw=true"><br>
*<sup>Powered by JohnTheRipper</sup>*
</p>

**Credit To:**<br>
JohnTheRipper - <a href="https://github.com/openwall/john">https://github.com/openwall/john</a><br>
7zip - <a href="https://www.7-zip.org/">https://www.7-zip.org/</a><br>
StarwberryPerl(Portable) - <a href="https://strawberryperl.com/releases.html">https://strawberryperl.com/releases.html</a><br>

**<p align="center">Instructions:</p>**

$${\color{yellow}1.) \space Double-click \space the \space script, \space and \space select \space a \space password \space protected \space ZIP, \space RAR, \space 7z, \space or \space PDF \space file}$$<br>

$${\color{yellow}2.) \space Wait \space for \space password..}$$<br>

When a password is found an alert window will appear, and the password(s) will be<br>
saved to the users desktop as: ZipRipper-Passwords.txt

*If the script is interrupted normally (by pressing the 'q' key to quit), resume will be enabled<br>.*
*An MD5 hash is created for each job, that is used to store the resume data, in: %AppData%\ZR-InProgress\[MD5HASH]<br>*
*to ensure multiple files with the same name can have InProgress jobs simultaneously. If a pending job is found the<br>*
*user is presented with the options of either resuming the job, or bypassing the resume feature and starting a new job.<br>*
*Note: When a job is completed the resume data is removed*

Current version provides support for hardware acceleration via OpenCL for:<br>
nVidia "GeForce" & "Quadro" and AMD "Radeon RX" & "Radeon Pro" cards.<br>

*ZIP, RAR, 7z, and PDF filetypes are supported

ZipRipper is portable, there are two different running modes; Online Mode, and Offline mode...

**Online Mode:** ZipRipper gathers its resources from the web (JohnTheRipper,7zip, and Portable Perl).<br>
Only the script itself and an internet connection are required for this mode.<br>

**Offline Mode:** ZipRipper uses/requires a local resource file [zr-offline.txt]. The presence of [zr-offline.txt] in<br>
the same folder as the script will force offline mode. An internet connection is not required for this mode.<br>
The file can be created by using Create-ZR-Offline.cmd, located in the .resources folder.

**Offline mode can be enabled by putting [zr-offline.txt] in the same folder as the ZipRipper before launch.**<br>
**[zr-offline.txt] creator:** <a href="https://github.com/illsk1lls/ZipRipper/blob/main/.resources/Create-ZR-Offline.cmd">https://github.com/illsk1lls/ZipRipper/blob/main/.resources/Create-ZR-Offline.cmd</a><br>
**[zr-offline.txt] archive:** <a href="https://github.com/illsk1lls/ZipRipper/raw/main/.resources/zr-offline.txt?download=">https://github.com/illsk1lls/ZipRipper/raw/main/.resources/zr-offline.txt?download=</a><br>

*UNC Paths are not supported. Mapped network drives are supported.*