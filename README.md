# 🧠 Zach's IT Home Lab Journey — A+ Certification & Help Desk Practice

## Welcome to my personal IT home lab repository!

This is a living, hands-on project where I document my journey toward earning the **CompTIA A+ certification**, building foundational IT skills, and landing a **remote Help Desk or IT Support role**.

Whether you're a beginner like me or someone looking to break into tech without a degree, this repo is here to:
- 🛠️ Share **real-world labs and troubleshooting practice**
- 📚 Track **A+ Core 1 (220-1101) & Core 2 (220-1102)** objectives
- 🎯 Build skills around Windows, Linux, networking, security, virtualization, and more
- 💻 Get hands-on using free tools like VirtualBox and open-source OSes

---

## 👇 Table of Contents

- [🛠️ Step 1: Build a Hands-On IT Lab at Home](#step-1-build-a-hands-on-it-lab-at-home-no-extra-cost)
- [🧰 IT Home Lab Setup](#your-it-home-lab-setup)
- [🎯 Hands-On Goal Mapping (A+ Domains)](#hands-on-goals-core-a-help-desk-topics)
- [🥊 VirtualBox vs VMware Workstation Player](#virtualbox-vs-vmware-workstation-player)
- [✅ VirtualBox Installation Guide](#step-by-step-download--install-virtualbox)

---

> 🔁 This repo will be updated as I move through topics, complete labs, and learn new skills. Everything is broken, fixed, and tested on a real system — no simulations here.

Feel free to follow along, fork the repo, or reach out if you're on a similar path.



## 🛠️ Step 1: Build a Hands-On IT Lab at Home (No Extra Cost)
This is your playground to experiment, break stuff, fix it, and document the whole process.

🧰 Your IT Home Lab Setup
You already have a laptop — that’s all you need to start:

✅ Install VirtualBox or VMware Workstation Player (free)

✅ Download and install:

🔸 Windows 10 ISO

🔸 Ubuntu (Linux) ISO

🔸 Optionally, Kali Linux (for security practice later)

Hands-on Goals (Core A+ & Help Desk Topics):
| Task                                                | What It Teaches                  | Core            |
| --------------------------------------------------- | -------------------------------- | --------------- |
| Install Windows in a VM                             | OS installation + virtualization | 220-1102        |
| Install Ubuntu in a VM                              | Linux basics                     | 220-1102        |
| Create file shares between VMs                      | Networking + permissions         | 220-1101 + 1102 |
| Install a printer in Windows                        | Peripherals & drivers            | 220-1101        |
| Use Task Manager, Event Viewer, CMD                 | Troubleshooting                  | 220-1102        |
| Simulate malware infection and removal              | Security concepts                | 220-1102        |
| Practice PC disassembly/reassembly videos (YouTube) | Hardware familiarity             | 220-1101        |



## 🥊 VirtualBox vs VMware Workstation Player

Feature	VirtualBox (by Oracle)	VMware Workstation Player (by VMware)
| Feature                      | **VirtualBox** (by Oracle)                      | **VMware Workstation Player** (by VMware)         |
| ---------------------------- | ----------------------------------------------- | ------------------------------------------------- |
| 💵 Cost                      | 100% Free (open-source)                         | Free for **personal use**                         |
| 💻 OS Support                | Windows, Linux, macOS, Solaris                  | Windows & Linux only                              |
| 🧩 Integration               | More flexible with multiple OSes and extensions | Slightly more stable & polished interface         |
| 🧪 Snapshots                 | ✅ Built-in snapshot support                     | ❌ Free version does **not** support snapshots     |
| 🛠️ Ease of Use              | Slightly more complex UI                        | Smoother, more user-friendly                      |
| 📚 Community Support         | Massive open-source community                   | Also large, with more enterprise focus            |
| 🐧 Linux Compatibility       | Excellent                                       | Also excellent (VMware runs Linux better overall) |
| 🧰 Customization             | Very customizable, great for labs               | Less tweakable in free version                    |
| 💾 File sharing (host/guest) | Easy with Guest Additions                       | Easy with VMware Tools                            |


## 🔍 Which One Should You Use?

✅ Use VirtualBox if...

🔹 You want snapshots (super useful for practicing break/fix)

🔹 You want to spin up multiple OSes, including macOS (eventually)

🔹 You prefer open-source tools

🔹 You want more flexibility for a DIY home lab setup

✅ Use VMware Workstation Player if...

🔹 You want better performance/stability out of the box

🔹 You're only running Windows or Linux guests

🔹 You don’t need snapshots or advanced lab features

🏁 My Recommendation for You:

✅ Go with VirtualBox — it’s more flexible for lab work, totally free, and widely used in IT training.

 - You can always try VMware later if you want a more “commercial” experience.

</br>

## 🔶 Let’s walk through the exact steps to download and install VirtualBox, including the correct files to get you started safely and smoothly.

✅ Step-by-Step: Download & Install VirtualBox </br>

1️⃣ Go to the Official VirtualBox Site</br>

👉 https://www.virtualbox.org/wiki/Downloads

🟢 You’ll see a section called "VirtualBox platform packages" — this is where you get the main program.

2️⃣ Download for Your System

Since you’re on Windows, click:

🔵 Windows hosts

🟢 This will download a file like:
```VirtualBox-7.x.x-yyyy-Win.exe```

✅ Save it somewhere easy to find (like your Desktop or Downloads folder).

## 3️⃣ Optional but Recommended: Extension Pack
Still on that same page, scroll down to:

📦 VirtualBox Extension Pack

Click this:

🔗``` All supported platforms```

🔸 This gives you extra features like:

🔸 USB 2.0/3.0 device support

🔸 VirtualBox RDP (Remote Desktop)

🔸 Host webcam passthrough

🔸 Encryption (for future practice)

🟢 It’ll download a file like:
```Oracle_VM_VirtualBox_Extension_Pack-7.x.x.vbox-extpack```

## 🖥️ Install VirtualBox

1. Run the downloaded ```.exe``` file.

2. Click Next through the prompts (leave defaults checked).

3. If you see a message saying you may be temporarily disconnected from the internet, it’s fine — it installs a virtual network adapter.

4. Click Install and let it run.

5. Click Finish and VirtualBox will open.

## 🔌 Install the Extension Pack (Optional but Recommended)
1. Open VirtualBox

2. Go to: File → Tools → Extension Pack Manager

3. Click the 📂 add icon, find the ```.vbox-extpack``` file you downloaded

4. Follow prompts to install

</br>

##🧪 Final Check
You should now see the VirtualBox Manager window open and ready like this:

```
+---------------------------------------+
| VirtualBox Manager                    |
|---------------------------------------|
| [ New ] [ Settings ] [ Start ]        |
|---------------------------------------|
| No virtual machines yet               |
+---------------------------------------+
```
From here, you're ready to install your first virtual machine.

 🖥️ Next steps:

🔹 Download Windows 10 ISO

🔹 Download Ubuntu ISO

Start creating VMs for practice.
</hr></br>

##Let’s get your **first virtual machines (VMs)** up and running. We’ll start with **Windows 10**, then move to **Ubuntu Linux** after.

---

## ✅ Step 1: Download Windows 10 ISO

### 🔗 Go to the official Microsoft download page:

👉 [https://www.microsoft.com/software-download/windows10](https://www.microsoft.com/software-download/windows10)

### 🖱 Scroll to:

> **"Create Windows 10 installation media"**

Click:

> **Download tool now**

This gives you a file:

```
MediaCreationTool22H2.exe
```

### 📥 Run the tool:

1. Accept the license agreement.

2. Choose:

   > ✅ **"Create installation media (USB flash drive, DVD, or ISO file)"**

3. On the next screen, leave defaults (English, Windows 10, 64-bit) checked and click **Next**.

4. Choose:

   > ✅ **ISO file**

5. Save the `.iso` file somewhere you’ll remember.

💡 The tool will download and create a file like:

```
Windows10.iso
```

Once done — you're ready to install it in VirtualBox.

---

## ✅ Step 2: Create a Windows 10 VM in VirtualBox

1. Open **VirtualBox** and click:

   > **New**

2. Name: `Windows 10`

   * Type: `Microsoft Windows`
   * Version: `Windows 10 (64-bit)`

3. Click **Next**

4. Memory Size:

   * Set **4096 MB (4 GB)** if you can spare it — or **2048 MB** minimum.

5. Click **Next**

6. Create Virtual Hard Disk:
   ✅ Select “Create a virtual hard disk now”

   * Disk size: **64 GB** recommended
   * File type: `VDI`
   * Storage: `Dynamically allocated`

7. Click **Create**

---

## ✅ Step 3: Mount the ISO & Start the VM

1. Select your new VM on the left in VirtualBox
2. Click **Start**
3. It will prompt you to select a startup disk:

   * Click the 📂 icon and browse to your downloaded `Windows10.iso`
4. Click **Start**

You’ll now enter the Windows installation process — just like installing on a real PC!

---

## 🛠 Installation Tips:

* Choose "Custom install" if it asks for install type
* Select the only unallocated disk shown
* Windows will install normally — this can take a few minutes
* You **don’t need a product key** to install — click:

  > “I don’t have a product key”
* You can skip signing in with a Microsoft account (choose offline account)

---

## 🎉 Done! You now have a Windows 10 VM to break, fix, and experiment in.

---

## 🚀 Up Next: Install Ubuntu ISO
</hr>
 Let’s set up **Ubuntu Linux** next — it’s essential for both the CompTIA A+ and IT Help Desk practice, plus it'll help you get comfortable with Linux fundamentals (which are key for cybersecurity later).

---

## ✅ Step 1: Download Ubuntu ISO

### 🔗 Go to the official Ubuntu site:

👉 [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)

### ✅ Choose:

> **Ubuntu 22.04.4 LTS** (Long Term Support – recommended for stability)

Click:

> **Download**

This will download a file like:

```
ubuntu-22.04.4-desktop-amd64.iso
```

Once downloaded, you’re ready to create the VM.

---

## ✅ Step 2: Create an Ubuntu VM in VirtualBox

1. Open **VirtualBox**, then click:

   > **New**

2. Name: `Ubuntu 22.04`

   * Type: `Linux`
   * Version: `Ubuntu (64-bit)`

3. Click **Next**

4. Memory Size:

   * Recommend **4096 MB (4 GB)** if you can
   * Minimum: **2048 MB**

5. Click **Next**

6. Create Virtual Hard Disk:

   * Choose: ✅ **Create a virtual hard disk now**
   * Disk type: `VDI`
   * Storage: `Dynamically allocated`
   * Size: **32 GB or more** recommended

7. Click **Create**

---

## ✅ Step 3: Mount the ISO and Boot the VM

1. Select your new **Ubuntu** VM

2. Click **Start**

3. You'll be prompted to select a startup disk:

   * Click the 📂 folder and select:

     ```
     ubuntu-22.04.4-desktop-amd64.iso
     ```

4. Click **Start**

---

## 🛠 Step 4: Install Ubuntu

When it boots up:

1. Click **Install Ubuntu**
2. Choose your language and keyboard layout
3. On “Updates and Other Software”:

   * Choose: ✅ **Normal Installation**
   * Check both boxes: **Download updates** + **Install 3rd party drivers**
4. For installation type:

   * Choose: ✅ **Erase disk and install Ubuntu** (only applies to the VM's virtual disk, not your real system — you're safe!)
5. Click **Continue**
6. Set your user account details and password
7. Let the installation finish (\~5–10 min)

Once done, it’ll ask to restart — let it reboot and **remove the ISO** if prompted.

---

### 🎉 You’re Done!

You now have:
✅ **Windows 10 VM**
✅ **Ubuntu Linux VM**

This gives you two systems to test networking between, practice installs, troubleshoot, and simulate real-world help desk tasks.

---

