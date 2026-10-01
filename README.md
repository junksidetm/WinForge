<div align="center">
<img src="assets\images\Real-BlackIcon.png" alt="WinForge Logo" width="192" /> <!-- Added the WinForge Logo -->
<h1>WinForge</h1>

<!-- Updated version to v5.0 -->
<a href="LICENSE"><img src="https://img.shields.io/github/license/mrdarksidetm/winforge?style=for-the-badge&label=License&labelColor=%237126eb&color=%239d70e6" alt="GitHub License"></a>
<a href="https://github.com/junksidetm/WinForge/commits"><img src="https://img.shields.io/github/last-commit/mrdarksidetm/winforge?style=for-the-badge&label=Last%20Commit&labelColor=%230f8c06&color=%235ecc56" alt="GitHub last commit"></a>
<a href="https://github.com/junksidetm/WinForge/releases/latest"><img src="https://img.shields.io/badge/Release-v5.0-gold?style=for-the-badge&labelColor=%235c5003" alt="GitHub Release"></a>
<a href=""><img src="https://img.shields.io/github/stars/mrdarksidetm/winforge?style=for-the-badge&label=Stars&labelColor=%238c2515&color=%23e8988b" alt="GitHub Repo stars"></a>
<a href=""><img src="https://img.shields.io/github/downloads/mrdarksidetm/winforge/total?style=for-the-badge&label=downloads&labelColor=%230e1433&color=%234457b8" alt="GitHub Downloads (all assets, all releases"></a>

<h3>WinForge v5.0: The Ultimate Win 11 Experience</h3>

[Features](https://github.com/junksidetm/WinForge?tab=readme-ov-file#-main-features) • [Installation](https://github.com/junksidetm/WinForge?tab=readme-ov-file#-installation) • [Contact](https://github.com/junksidetm/winforge#%EF%B8%8F-contact) • [License](https://github.com/junksidetm/winforge#%EF%B8%8F-licensec)

<!-- For releases in both Github and Gitlab -->
<a href="https://github.com/junksidetm/WinForge/releases/latest"><img src="assets/images/Github.png" height=80 alt="Github Release" target=blank></a>
<a href="https://gitlab.com/mrdarksidetm/WinForge/releases/latest"><img src="assets/images/Gitlab.png" height=80 alt="Gitlab Release" target=blank></a>

</div>

<img src="assets\images\WinForge-Preview.png" alt="Preview" target=blank /> <!-- WinForge Banner -->

## 🌟 Main Features (v5.0 Next-Gen)

* **✅ Windows Recall & AI Purge:** Securely remove Microsoft Recall and Copilot to reclaim your privacy and system resources.
* **🎮 Ultimate Game Mode:** One-click optimization for maximum FPS, low latency, and high-performance power profiles.
* **🔄 Winget App Updater:** Automatically keep all your installed applications updated to their latest secure versions.
* **🛠️ Chris Titus WinUtil Integration:** One-click debloating, optimization, and Windows customization using industry-standard utilities.
* **🚀 MASSGRAVE (MAS) Integration:** Secure, permanent Windows activation using trusted hardware-bound methods.
* **⚡ Speed Optimized DNS:** Cloudflare or AdGuard DNS for maximum internet speed with privacy protection and DoH encryption.
* **🧹 Smart Debloating:** Safely remove pre-installed Windows apps (Cortana, OneDrive notifications, Xbox, Games) and unwanted background processes.
* **🔒 Privacy & Security Hardening:** Disable telemetry, data collection, and block invasive Windows services without breaking functionality.
* **🎨 Terminal Customization:** Oh My Posh theme engine installation for a beautiful, professional PowerShell terminal experience.

WinForge is your complete Windows 11 optimization toolkit - fast, secure, and professional-grade! 🎉

# 🪄 Installation

**This is a Powershell script that is not digitally signed so you need to run some commands.**

1. Download the zip from the latest [releases](https://github.com/junksidetm/WinForge/releases/latest) <!-- Link to the latest release -->
2. Unzip it from any of the Unzipping Program
3. Open `Terminal (Admin)` by right clicking on start button
4. Paste this command.

```powershell.exe
Set-ExecutionPolicy Unrestricted -Scope CurrentUser
cd "Downloads\WinForge" #remove the "path" with the actual path of the folder. 
.\WinForge.ps1 #As it is in your downloads folder, Windows asks you do you wanna run it or not. Type R and press enter.
R
```

# 📲 Import Configrations and Files

I have also provided some files for **Chris Titus Utility** & **Winhance**. That you can import in those apps and make the process more streamlined. All the `Import Files` are labeled.

> [!NOTE]
> If you have downloaded the zip format then it contains the pre configured import files for both **Chris Titus Utility** and **Winhance**

And you're done. The script will ask you questions of what you wanna do?
If you wanna know the exact things that the script is gonna do then [visit this page](docs/working.md)</n> <!-- Linked new page for all the code actions and steps it will perform -->

The default is set to **NO**.

## For Chris Titus Utility

<img src="assets/images/ChrisTitus-Import.png" alt="Import Chris" />

1. Let this screen be opened.
2. Click on the Gear (Settings icon) at the top right corner as illustrated in the [image](assets/images/ChrisTitus-Import.png)
3. A menu will open to **Import** the configuration
4. Go to `Install` section and select the apps you wanna install
5. `Tweaks`section is the best & highly configured and if you don't know what every thing is saying, just click **Run Tweaks** at the bootom left side

## For Winhance

<img src="assets/images/Winhance-import.png" alt="Import Chris" />

1. Let this screen be opened,
2. Click on the **Folder** like icon in upper right corner as illustrated in the [image](assets/images/Winhance-import.png)
3. then Import the configrations

Enjoy 🎉

## For Activation

<img src="assets\images\MAS-Activation.png" alt="MAS Activation" />

1. When this opens, all the keys are locked and you can oonly use numbers (1,2,3....)
2. RECOMMENDED for windows activation use 1
3. RECOMMENDED for Office use 2

## ⚙️ Workings

If you wanna see the workings, either check the `Source Code` or [visit this page](docs/working.md)

## 💫 Credits

* Chris Titus Tech- [WinUtil](https://github.com/ChrisTitusTech/winutil)
* Mestechtips - [WinHance](https://github.com/memstechtips/Winhance)
* Cloudflare - [Cloudflare DNS](https://developers.cloudflare.com/1.1.1.1/setup/)
* Adguard - [Adguard DNS](https://adguard-dns.io/en/public-dns.html)
* Microsoft Activation Script - [MAS](https://github.com/massgravel/Microsoft-Activation-Script)
* Edge WebView2 Runtime - [WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)
* Oh My Posh - [Oh My Posh](https://ohmyposh.dev/)

# ✉️ Contact

For any questions or feedback, feel free to open an issue on GitHub or contact [contact.dsidetm@gmail.com](mailto:contact.dsidetm@gmail.com)

# ©️ License

This project is licensed under the MIT license. See the `LICENSE` file for details.

# ☕ Sponsor the Forge

If this sparked joy (or saved your sanity), fuel the fire!

<div align="center">

<table>
  <tr>
    <td>
      <a href="https://www.buymeacoffee.com/mrdarksidetm" target="_blank"><img src="docs/assets\images\support\Buymecoffe-Square.png" alt="Buy Me a Coffee" height="80"></a>
    </td>
    <td>
      <a href="https://ko-fi.com/H2H21N0OAT" target="_blank"><img src="docs/assets\images\support\Kofi-Square.png" alt="Ko-fi" height="80">
</a>
    </td>
    <td>
      <a href="https://www.upi.me/pay?pa=abhisidetm@ptyes&am=150" target="_blank"><img src="docs/assets\images\support\Gpay.png" alt="Gpay" height="80"></a>
    </td>
  </tr>
</table>
</div>
<br>

**🌟 Future Tease:** Signed EXE wrapper incoming—stay tuned via Releases. Questions? Open an Issue. Let's build better Windows, one forge at a time.

<!--  
If you're reading that means you have visited to the depts just like I had and you alos love code and ways to customise your machine your way.
Thank you, hope our paths cross once again
But hey for today it's time to leave
Love from India <3
-->