# 📝 OpenOffice.org 2.4 – README

**Welcome to OpenOffice.org 2.4!**  
For the latest version of this README, visit:  
👉 [openoffice.org/welcome/readme.html](http://www.openoffice.org/welcome/readme.html)

---

## 📌 About This File

This document contains important information about using, installing, and troubleshooting OpenOffice.org 2.4. Please read this before beginning.

To learn more about OpenOffice.org and how to get involved, visit:  
🔗 [About the Project](http://www.openoffice.org/about_us/introduction.html)

---

## 🆓 Is OpenOffice.org Really Free?

Yes. OpenOffice.org is **completely free** for:
- Government
- Businesses
- Educational institutions
- Private users

For license details, visit:  
🔗 [openoffice.org/license.html](http://www.openoffice.org/license.html)

---

## 💻 System Requirements

- **Operating System**: Windows 98, ME, NT (SP6 or later), 2000, XP  
- **Processor**: Pentium-compatible  
- **RAM**: 64 MB minimum  
- **Disk Space**:  
  - 250 MB (Standard installation)  
  - 300 MB (CJK version)  
  - 500 MB free space required after installation  
- **Display**: 800x600 resolution, 256 colors or higher

---

## 🛠️ Installation Notes

- Close all other programs before installation.
- Make sure you have **enough free space in the temporary directory**.
- Administrator rights are required.
- After uninstalling an older version, run the new installer again and choose **Repair** to ensure proper registration.
- Copy/paste between OpenOffice.org 1.x and 2.4 may not work correctly. Use `Edit > Paste Special` to choose a compatible format.
- On Windows 98, installing Java during setup might prompt an unnecessary reboot. Restart the installer if needed.

---

## 🖱️ ALPS/Synaptics Touchpad Scrolling (Windows Only)

Scrolling may not work by default. To enable it:

1. Edit:  
   `C:\Program Files\Synaptics\SynTP\SynTPEnh.ini`
2. Add the following lines:
    [OpenOffice.org] FC = "SALFRAME" SF = 0x10000000 SF |= 0x00004000

3. Restart your system.

> Note: File location may vary by Windows version.

---

## 🧩 Known Issues & Workarounds

### Startup Problems
- Commonly caused by outdated **graphics drivers**.
- Update your driver or revert to the one provided by your OS.
- To resolve 3D view issues, disable OpenGL in:  
  `Tools > Options > OpenOffice.org > View > 3D View`

### Email Sending Crashes
- Crashes when sending files via `File > Send > Email` may be due to Windows MAPI DLL issues.
- Learn more at: [Microsoft Support](http://www.microsoft.com) (search: "mapi dll")

---

## ♿ Accessibility: ZoomText Compatibility

To use **Ai Squared ZoomText**, ensure you're using version **7.11 or newer**, released after **June 12, 2002**.

---

## ⌨️ Keyboard Shortcuts

Only shortcuts not used by the operating system will work.  
To resolve conflicts:
- Change system-assigned shortcuts
- Customize OpenOffice.org shortcuts via the settings menu  
  (`Tools > Customize > Keyboard`)

---

## 📩 Support

- Visit: [Mailing Lists](http://www.openoffice.org/mail_list.html)
- Ask questions: `users@openoffice.org` (requires subscription)
- FAQ: [user-faq.openoffice.org](http://user-faq.openoffice.org/)

---

## 🐞 Reporting Bugs

Help us improve OpenOffice.org!  
Use [IssueZilla](http://www.openoffice.org/issues/) to report platform-specific bugs and issues.

---

## 🤝 Get Involved

Want to contribute? Start here:
- Visit: [How to Get Started](http://development.openoffice.org/todo.html)
- Subscribe to mailing lists:  
  - `announce@openoffice.org` – News (low traffic)  
  - `discuss@openoffice.org` – User forum (high traffic)  
  - `dev@openoffice.org` – Developer discussions  
  - `dev@marketing.openoffice.org` – Marketing contributors

---

## 📣 Join a Project

Explore projects beyond coding:  
- [Project Directory](http://projects.openoffice.org/index.html)
- Help with: Documentation, Localization, Porting, Groupware, Marketing
- Join the [Marketing Communications Network](http://marketing.openoffice.org/contacts.html)

---

## 🔐 Registration

Registration is optional but encouraged. Your data helps improve OpenOffice.org.  
Register anytime at:  
🔗 [openoffice.org/welcome/registration-site.html](http://www.openoffice.org/welcome/registration-site.html)

---

## 🔍 User Survey

Help shape future versions by completing our [User Survey](http://www.openoffice.org).

---

## 📜 Third-Party & Source Credits

- Portions © 1998–1999 James Clark  
- Portions © 1996, 1998 Netscape Communications Corporation

---

Enjoy using OpenOffice.org 2.4!  
— The OpenOffice.org Community

