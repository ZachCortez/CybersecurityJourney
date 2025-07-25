# 🧠 Zach's IT Home Lab Journey — A+ Certification & Help Desk Practice

Welcome to my personal IT home lab repository!

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



🛠️ Step 1: Build a Hands-On IT Lab at Home (No Extra Cost)
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



🥊 VirtualBox vs VMware Workstation Player

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


🔍 Which One Should You Use?

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

🔶 Let’s walk through the exact steps to download and install VirtualBox, including the correct files to get you started safely and smoothly.

✅ Step-by-Step: Download & Install VirtualBox
1️⃣ Go to the Official VirtualBox Site
👉 https://www.virtualbox.org/wiki/Downloads

🟢 You’ll see a section called "VirtualBox platform packages" — this is where you get the main program.

2️⃣ Download for Your System

Since you’re on Windows, click:

🔵 Windows hosts

🟢 This will download a file like:
```VirtualBox-7.x.x-yyyy-Win.exe```

✅ Save it somewhere easy to find (like your Desktop or Downloads folder).

3️⃣ Optional but Recommended: Extension Pack
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

🖥️ Install VirtualBox

1. Run the downloaded ```.exe``` file.

2. Click Next through the prompts (leave defaults checked).

3. If you see a message saying you may be temporarily disconnected from the internet, it’s fine — it installs a virtual network adapter.

4. Click Install and let it run.

5. Click Finish and VirtualBox will open.

🔌 Install the Extension Pack (Optional but Recommended)
1. Open VirtualBox

2. Go to: File → Tools → Extension Pack Manager

3. Click the 📂 add icon, find the ```.vbox-extpack``` file you downloaded

4. Follow prompts to install

</br>

🧪 Final Check
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
