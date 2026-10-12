<!-- ═══════════════════════════════════════════════════════════ -->
<!--       GHOST GIRL JAILX — INSTALLATION GUIDE (v1.7.2)        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=28&pause=1000&color=FFD700&center=true&vCenter=true&width=800&height=80&lines=%F0%9F%91%BB+INSTALLATION+GUIDE+%F0%9F%91%BB;Ghost+Girl+JailX+v1.7.2" alt="Installation Banner" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24,30&height=100&section=header&text=★%20★%20★%20★%20★&fontSize=30&fontColor=FFD700&animation=twinkling" />

</div>

# 👻 Ghost Girl JailX — Installation Guide

Welcome! This guide walks you through installing **Ghost Girl JailX v1.7.2** on your PlayStation 3.

> ⚠️ **Follow every step in order.** Skipping steps can cause the installer to fail or the console to hang.

---

## ✅ Requirements

Before you start, make sure you have:

| Item | Details |
|------|---------|
| 🎮 **Console** | Compatible PS3 (see [COMPATIBILITY.md](COMPATIBILITY.md)) |
| 💾 **USB Stick** | Formatted to **FAT32** with **MBR** partition table |
| 💻 **PC** | Windows / macOS / Linux to prepare the USB |
| 📦 **File** | `GhostGirlJailX.zip` from the [Releases](../../releases) page |
| 🎮 **Controller** | Official DualShock 3 (connected via USB) |

---

<div align="center">

## 📥 <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">1</span> — <span style="color:#FFC700;">D</span><span style="color:#FFB800;">O</span><span style="color:#FFA800;">W</span><span style="color:#FFD700;">N</span><span style="color:#FFC700;">L</span><span style="color:#FFB800;">O</span><span style="color:#FFA800;">A</span><span style="color:#FFD700;">D</span> <span style="color:#FFC700;">T</span><span style="color:#FFB800;">H</span><span style="color:#FFA800;">E</span> <span style="color:#FFD700;">Z</span><span style="color:#FFC700;">I</span><span style="color:#FFB800;">P</span>

</div>

1. Go to the [Releases](../../releases) page of this repo.
2. Download the latest file: **`GhostGirlJailX.zip`**
3. Save it somewhere easy to find on your PC (e.g. your Desktop).

---

<div align="center">

## 📂 <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">2</span> — <span style="color:#FFC700;">E</span><span style="color:#FFB800;">X</span><span style="color:#FFA800;">T</span><span style="color:#FFD700;">R</span><span style="color:#FFC700;">A</span><span style="color:#FFB800;">C</span><span style="color:#FFA800;">T</span> <span style="color:#FFD700;">T</span><span style="color:#FFC700;">H</span><span style="color:#FFB800;">E</span> <span style="color:#FFA800;">Z</span><span style="color:#FFD700;">I</span><span style="color:#FFC700;">P</span>

</div>

1. Right-click `GhostGirlJailX.zip`.
2. Choose **Extract All** (Windows) or **Open** (macOS/Linux).
3. Extract the contents to a folder on your PC.

You should now see the **files and folders** ready to copy to your USB.

---

<div align="center">

## 💾 <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">3</span> — <span style="color:#FFC700;">F</span><span style="color:#FFB800;">O</span><span style="color:#FFA800;">R</span><span style="color:#FFD700;">M</span><span style="color:#FFC700;">A</span><span style="color:#FFB800;">T</span> <span style="color:#FFA800;">T</span><span style="color:#FFD700;">H</span><span style="color:#FFC700;">E</span> <span style="color:#FFB800;">U</span><span style="color:#FFA800;">S</span><span style="color:#FFD700;">B</span> <span style="color:#FFC700;">T</span><span style="color:#FFB800;">O</span> <span style="color:#FFA800;">F</span><span style="color:#FFD700;">A</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">3</span><span style="color:#FFA800;">2</span>

</div>

1. Insert your USB stick into your PC.
2. Format it to **FAT32**.

**Windows:**
- Open **File Explorer** → right-click the USB drive → **Format**
- File system: **FAT32**
- Click **Start**

**macOS:**
- Open **Disk Utility** → select the USB stick
- Click **Erase**
- Format: **MS-DOS (FAT)**
- Scheme: **Master Boot Record (MBR)**

**Linux:**

```bash
sudo mkfs.vfat -F 32 /dev/sdX1
```

Replace `/dev/sdX1` with your actual USB device (check with `lsblk`).

> ⚠️ **Important:** The partition scheme must be **MBR**, not GPT. The PS3 will not read GPT drives.

---

<div align="center">

## 📁 <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">4</span> — <span style="color:#FFC700;">C</span><span style="color:#FFB800;">O</span><span style="color:#FFA800;">P</span><span style="color:#FFD700;">Y</span> <span style="color:#FFC700;">F</span><span style="color:#FFB800;">I</span><span style="color:#FFA800;">L</span><span style="color:#FFD700;">E</span><span style="color:#FFC700;">S</span> <span style="color:#FFB800;">T</span><span style="color:#FFA800;">O</span> <span style="color:#FFD700;">U</span><span style="color:#FFC700;">S</span><span style="color:#FFB800;">B</span>

</div>

1. Open the folder where you extracted `GhostGirlJailX.zip`.
2. Select **ALL files and folders** inside it.
3. **Copy** them and **paste** them onto the **root** of the USB stick.

> ⚠️ **Do NOT** put the files inside another folder on the USB — they must sit directly at the root (e.g. `E:\` on Windows, `/Volumes/USB/` on macOS).

4. Wait until the copy is **100% complete** before continuing.

---

<div align="center">

## ⏏️ <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">5</span> — <span style="color:#FFC700;">S</span><span style="color:#FFB800;">A</span><span style="color:#FFA800;">F</span><span style="color:#FFD700;">E</span><span style="color:#FFC700;">L</span><span style="color:#FFB800;">Y</span> <span style="color:#FFA800;">E</span><span style="color:#FFD700;">J</span><span style="color:#FFC700;">E</span><span style="color:#FFB800;">C</span><span style="color:#FFA800;">T</span>

</div>

1. **Safely eject / unmount** the USB stick from your PC before removing it.
   - Windows: Right-click USB → **Eject**
   - macOS: Drag USB icon to Trash, or click ⏏️ in Finder
   - Linux: `sudo umount /dev/sdX1`
2. Physically remove the USB stick.

---

<div align="center">

## 📡 <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">6</span> — <span style="color:#FFC700;">P</span><span style="color:#FFB800;">R</span><span style="color:#FFA800;">E</span><span style="color:#FFD700;">P</span> <span style="color:#FFC700;">T</span><span style="color:#FFB800;">H</span><span style="color:#FFA800;">E</span> <span style="color:#FFD700;">P</span><span style="color:#FFC700;">S</span><span style="color:#FFB800;">3</span>

</div>

**Before plugging the USB in**, do the following on your PS3:

1. Turn **Wi-Fi OFF**
   - `Settings → Network Settings → Internet Connection → Disable`
2. Turn **Auto Sign-In OFF** (if it was enabled)
   - `Users → Auto Sign-In → Off`
3. Land on the **home screen (XMB)** and **wait 1–2 minutes** without touching anything.

> 💡 This prevents the console from trying to reach PSN during the install process and gives the system time to settle.

---

<div align="center">

## 🔌 <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">7</span> — <span style="color:#FFC700;">P</span><span style="color:#FFB800;">O</span><span style="color:#FFA800;">W</span><span style="color:#FFD700;">E</span><span style="color:#FFC700;">R</span> <span style="color:#FFB800;">O</span><span style="color:#FFA800;">F</span><span style="color:#FFD700;">F</span> <span style="color:#FFC700;">&</span> <span style="color:#FFB800;">P</span><span style="color:#FFA800;">L</span><span style="color:#FFD700;">U</span><span style="color:#FFC700;">G</span> <span style="color:#FFB800;">I</span><span style="color:#FFA800;">N</span>

</div>

1. **Turn the console completely OFF** — a full shutdown, **not standby**.
   - Hold the power button until the light turns **red**.
2. Plug the USB stick into the **right-most front USB port** of the PS3.

> ⚠️ **Use the RIGHT USB port.** The PS3 is picky — the left port often won't read update files.[citation:8][citation:16]

---

<div align="center">

## 🎮 <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">8</span> — <span style="color:#FFC700;">B</span><span style="color:#FFB800;">O</span><span style="color:#FFA800;">O</span><span style="color:#FFD700;">T</span> <span style="color:#FFC700;">T</span><span style="color:#FFB800;">H</span><span style="color:#FFA800;">E</span> <span style="color:#FFD700;">P</span><span style="color:#FFC700;">S</span><span style="color:#FFB800;">3</span>

</div>

1. Press the **Power button** to turn the console **ON normally**.
2. Wait for it to boot to the **normal home screen (XMB)**.
3. Navigate to the **Settings** column.
4. Scroll down to **System Update** and press **X**.
5. Select **Update via Storage Media**.
6. The PS3 will detect the **Evilnat CFW** file on the USB stick.
7. Confirm the update and let it install.
   > ⚠️ **DO NOT power off, unplug the USB, or touch the console during this step.** Interrupting the flash can brick your PS3.
8. When the flash completes, the console will **reboot automatically**.
9. Let it boot fully — you should now see the **Evilnat CFW** branding on the boot screen.

> 💡 If the PS3 says **"No applicable update data was found"**, see the troubleshooting section below.

---

<div align="center">

## ✅ <span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">9</span> — <span style="color:#FFC700;">V</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">R</span><span style="color:#FFD700;">I</span><span style="color:#FFC700;">F</span><span style="color:#FFB800;">Y</span>

</div>

After Evilnat CFW is installed and the console reboots:

- The **Evilnat CFW** logo should appear during boot.
- The **Ghost Girl JailX** branding should appear on the home screen.
- The version should display **1.7.2**.

If all three are true — 🎉 **you're fully jailbroken!**

---

<div align="center">

## 🛠️ <span style="color:#FFD700;">T</span><span style="color:#FFC700;">R</span><span style="color:#FFB800;">O</span><span style="color:#FFA800;">U</span><span style="color:#FFD700;">B</span><span style="color:#FFC700;">L</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">S</span><span style="color:#FFD700;">H</span><span style="color:#FFC700;">O</span><span style="color:#FFB800;">O</span><span style="color:#FFA800;">T</span><span style="color:#FFD700;">I</span><span style="color:#FFC700;">N</span><span style="color:#FFB800;">G</span>

</div>

| ❌ Problem | ✅ Fix |
|-----------|-------|
| **"No applicable update data was found"** | 1. Make sure the USB is **FAT32 + MBR** [citation:4][citation:10]<br>2. Confirm files are in **`PS3/UPDATE/PS3UPDAT.PUP`** (exact case) [citation:4][citation:10]<br>3. Try the **right-most USB port** [citation:8][citation:16]<br>4. **Unplug the controller** after pressing Start+Select, then wait [citation:4][citation:16]<br>5. Try a **smaller USB stick** (8–16 GB works best) [citation:10] |
| Console doesn't detect USB at all | Check the USB appears in **Music** or **Photos** on the XMB. If it doesn't, the PS3 can't read it — try a different drive.[citation:8] |
| File named `PS3UPDAT.PUP.PUP` | Turn on **file extensions** on your PC and rename it to just `PS3UPDAT.PUP` [citation:10] |
| Evilnat install fails (error 8002F957) | Your console's flash is **not patched**. You must use **PS3 Toolset** (ps3toolset.com/bgtoolset) first to patch the firmware, then retry the CFW install.[citation:12][citation:14] |
| Install freezes at 70% | Same as above — flash patch is missing. Re-patch via PS3 Toolset.[citation:12] |
| Console bricked / won't boot | Use **Safe Mode** (Recovery Mode) to restore. See [Safe Mode guide](https://consolemods.org/wiki/PS3:Safe_Mode).[citation:9][citation:15] |

---

<div align="center">

## 📌 <span style="color:#FFD700;">Q</span><span style="color:#FFC700;">U</span><span style="color:#FFB800;">I</span><span style="color:#FFA800;">C</span><span style="color:#FFD700;">K</span> <span style="color:#FFC700;">C</span><span style="color:#FFB800;">H</span><span style="color:#FFA800;">E</span><span style="color:#FFD700;">C</span><span style="color:#FFC700;">K</span><span style="color:#FFB800;">L</span><span style="color:#FFA800;">I</span><span style="color:#FFD700;">S</span><span style="color:#FFC700;">T</span>

</div>

Before installing, confirm:

- [ ] USB formatted to **FAT32**
- [ ] Partition scheme is **MBR**
- [ ] Files in **`PS3/UPDATE/PS3UPDAT.PUP`** (exact case)
- [ ] USB **safely ejected** before removal
- [ ] PS3 **Wi-Fi OFF**
- [ ] PS3 **Auto Sign-In OFF**
- [ ] Waited **1–2 minutes** on home screen
- [ ] Console **fully powered off**
- [ ] USB plugged into **right-most front port**
- [ ] Console booted to **normal home screen** (not recovery)
- [ ] **Evilnat CFW** installed via System Update
- [ ] Console rebooted with **Evilnat branding** visible

---

<div align="center">

## 💜 <span style="color:#FFD700;">N</span><span style="color:#FFC700;">E</span><span style="color:#FFB800;">E</span><span style="color:#FFA800;">D</span> <span style="color:#FFD700;">H</span><span style="color:#FFC700;">E</span><span style="color:#FFB800;">L</span><span style="color:#FFA800;">P</span> <span style="color:#FFD700;">?</span>

</div>

Still stuck? Open an [Issue](../../issues) with:

- Your **PS3 model** (Fat / Slim / Super Slim)
- Your **firmware version**
- The **exact step** where it fails
- Any **error messages** shown on screen

We'll get you sorted 👻

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=20&pause=500&color=FFD700&center=true&vCenter=true&width=700&height=60&lines=★+★+★+★+★;%E2%98%85+GOOD+LUCK+%E2%98%85;★+★+★+★+★" alt="Footer" />

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24,30&height=100&section=footer&animation=twinkling&fontColor=FFD700" />

**Made with 💜 and ⭐ metallic gold by the Ghost Girl JailX team.**

</div>
