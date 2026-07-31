# Aon Pro Studio — Downloads

**Windows 10 / 11 · 64-bit · AI video production studio**

This repository hosts the official Windows installer for Aon Pro Studio.
It contains **downloads only — no source code**.

- Product site — https://aonprostudio.netlify.app
- Redeem your code — https://aonprostudio.netlify.app/redeem
- Support — aonprostudio@gmail.com

---

## Download

**[⬇ Download the latest release](https://github.com/Gemdu0/aon-pro-studio-downloads/releases/latest/download/AonProStudio-Setup.exe)**

Or use the permanent direct link, which always points at the newest build:

```
https://github.com/Gemdu0/AonProStudio-Releases/releases/latest/download/AonProStudio-Setup.exe
```

Older builds are on the [Releases](https://github.com/Gemdu0/AonProStudio-Releases/releases)
page, each with its own release notes.

---

## Before you install

| | |
|---|---|
| **Operating system** | Windows 10 or Windows 11, 64-bit. There is no macOS, Linux, or browser version. |
| **License key** | Required. It is in your purchase confirmation email, or in your account on the store where you bought Aon Pro Studio. |
| **OpenAI API key** | Required. Aon Pro Studio is a bring-your-own-key app — AI generation runs on your own provider account. |
| **Internet** | Required to activate your license and to call AI providers. |

> [!IMPORTANT]
> **AI usage is billed separately from your license.**
> Your license covers the software only. OpenAI, MiniMax, and ElevenLabs bill your own
> accounts directly for what you generate. See the
> [API key setup guide](https://aonprostudio.com/api-keys.html) and the
> [API cost guide](https://aonprostudio.com/api-costs.html) before you start.

---

## Install and activate

1. **Download** `AonProStudio-Setup.exe` from the link above.
2. **Run the installer.** If Windows SmartScreen shows a blue *"Windows protected your PC"*
   dialog, click **More info → Run anyway**. See [Windows blocked the installer](#windows-blocked-the-installer) below.
3. **Launch Aon Pro Studio.** The activation screen opens on the first launch.
4. **Paste your license key** and click **Activate License**. If you see the email
   sign-in screen instead, click *Activate with license key* to switch.
5. **Open Settings and add your API keys** — OpenAI is required; MiniMax and ElevenLabs
   are optional for higher-quality voices and image-to-video.

Full walkthrough with screenshots: **https://aonprostudio.com/redeem**

---

## Verify your download (optional)

Every release lists a SHA-256 checksum in its release notes. To confirm your copy matches,
run this in PowerShell and compare the result:

```powershell
Get-FileHash .\AonProStudio-Setup.exe -Algorithm SHA256
```

Only download Aon Pro Studio from this repository or from
[aonprostudio.com](https://aonprostudio.com). Files from anywhere else are not ours and
are not supported.

---

## Windows blocked the installer

SmartScreen warns about installers it has not seen many times yet. This is expected for a
newly released desktop app and is **not** a virus detection.

1. Confirm the file came from this repository or from aonprostudio.com.
2. Click **More info** in the dialog.
3. Click **Run anyway**.

If your antivirus quarantines the file, restore it from the quarantine list rather than
turning protection off globally. On a company-managed PC, ask your IT administrator first.
Still stuck? Email aonprostudio@gmail.com.

---

## Licensing

- **One key activates one PC.** The key is tied to that machine when you activate it, so a
  second PC returns *"This license key is already registered on another device."*
- **New PC, Windows reinstall, or hardware change?** Email **aonprostudio@gmail.com** with
  the subject **License transfer**, and include your license key, the email address you
  purchased with, and a one-line reason. We reset the key within one to two business days,
  then you activate on the new PC exactly as you did the first time.
- **Single plan, no stacking.** One code unlocks the entire app. There are no tiers, so a
  second code adds nothing to an already-activated PC — use each code on a separate PC.
- Licenses are for one person's use and cannot be shared or resold.

---

## Support

Email **aonprostudio@gmail.com** for anything about downloads, activation, transfers, or
the app itself. We reply within one to two business days. Include your license key and a
screenshot of any error message for a faster answer.

The Issues tab on this repository is **not monitored** — please use email.

Common activation errors and what they mean are listed on the
[redemption page](https://aonprostudio.com/redeem#support).

---

## Legal

Aon Pro Studio is proprietary software. The installer published here may not be
redistributed, mirrored, repackaged, or resold.

- [Terms of Service](https://aonprostudio.com/terms.html)
- [Privacy Policy](https://aonprostudio.com/privacy.html)

---
