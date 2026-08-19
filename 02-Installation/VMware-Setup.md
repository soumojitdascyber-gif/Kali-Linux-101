# ⚙️ Kali Linux Pre-built VM Setup & Mouse Cursor Fix (VMware)

## 🚀 Step 1: Extract & Load
1. Right-click on the downloaded Kali `.7z` file -> Navigate to **7-Zip** -> Click **"Extract to kali-linux-..."**
2. Open **VMware Workstation**.
3. Click on **"Open a Virtual Machine"**.
4. Navigate to the extracted folder, select the `.vmx` file, and click **Open**.

## 🔑 Step 2: First Boot & Login
1. Click on **"Power on this virtual machine"**.
2. At the login screen, enter:
   * **Username:** `kali`
   * **Password:** `kali`

## 🛠️ Step 3: Invisible Mouse Cursor Fix
*If your mouse cursor is invisible after booting into Kali Linux:*

1. **Suspend** or **Power Off** the virtual machine.
2. Right-click on the VM's name -> Go to **Manage** -> Select **Change Hardware Compatibility...**
3. From the dropdown menu, select **"Workstation 17.x"** -> Click **Next**.
4. Select **"Alter this virtual machine"** -> Click **Finish**.
5. **Restart/Resume** the VM.
6.
