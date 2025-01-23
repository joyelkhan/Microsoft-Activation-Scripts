# Microsoft Activation Scripts 

An **open-source** tool to activate **Windows** and **Office**, featuring multiple activation methods including **HWID**, **Ohook**, **KMS38**, and **Online KMS**, along with **advanced troubleshooting**.

---

### 🌟 **Features**
- **HWID (Digital License)** method for permanent **Windows** activation.
- **Ohook** method for permanent **Office** activation.
- **KMS38** method for activating **Windows/Server** until the year 2038.
- **Online KMS** method for activating **Windows/Server/Office** for 180 days (renewable indefinitely).
- **Advanced activation troubleshooting** for problem solving.
- **$OEM$** folders for pre-activation.
- **Change Windows or Office Edition** effortlessly.
- **Check Windows/Office Activation Status**.
- Available in **All-in-One** or **Separate Files** versions.
- **Open Source** and based on **Batch Scripts**.
- **Reduced antivirus detection**.

---

### 📥 **Download & Usage**

#### Method 1 - PowerShell (Windows 8 and later) ❤️
1. Open **PowerShell** (Not CMD). To do this, right-click the Windows start menu and select **PowerShell** or **Terminal**.
2. Copy and paste the following command into PowerShell and press **Enter**:
   ```powershell
   irm https://get.activated.win | iex
   ```

3. You'll see the activation options. 
   - Choose `[1]` for **HWID** to activate **Windows**.
   - Choose `[2]` for **Ohook** to activate **Office**.

And that's it! You're done!

#### Method 2 - Traditional (Windows 7 and later)
Alternatively, you can use the older method (though it may be deprecated soon):
```powershell
irm https://massgrave.dev/get | iex
```

**Note**: The `get.activated.win` URL might be blocked by some DNS services due to its newness.

---

### ⚠️ **Important Notes**
- The **IRM** command in PowerShell downloads a script from the provided URL, and the **IEX** command executes it.
- Always verify the URL before executing the command and ensure you're downloading from a trusted source.
- Be cautious of **malware** disguised as MAS scripts using modified URLs.

---

### 🆕 **MAS Latest Release**
- **Last Release**: v2.9 (20-Dec-2024)
- Available via:
  - **GitHub** 
  - **Azure DevOps** 
  - **Self-hosted Git**

---

### 🔑 **Activation Methods Summary**

| **Activation Type** | **Supported Product**         | **Activation Period**          | **Internet Required?** |
|---------------------|-------------------------------|--------------------------------|------------------------|
| **HWID**            | **Windows 10-11**              | **Permanent**                  | Yes                    |
| **Ohook**           | **Office**                     | **Permanent**                  | No                     |
| **KMS38**           | **Windows 10-11-Server**       | **Till Year 2038**             | No                     |
| **Online KMS**      | **Windows/Office**             | **180 Days (Lifetime with Renewal)** | Yes                    |

For further details, please refer to the respective **Docs** for each activation method.

---

### 📋 **For Unsupported Products**
If you're looking to activate unsupported products, such as **Office for Mac**, check [here](#) for more information.

---

By using **MAS**, you're unlocking a free, open-source solution for managing your **Windows** and **Office** activations efficiently!

---
