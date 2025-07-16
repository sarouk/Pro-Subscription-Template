<div align="center">
  
![Screenshot](tmp.png)

# 📌 Customized User Page Template for Marzban Panel (Marzban Template)
</div>

## 🎨 Introduction

This project is a modified version of the original template from [Mrclocks/Pro-Subscription-Template](https://github.com/Mrclocks/Pro-Subscription-Template).

> ⚠️ This is **not** the official version.

## ✅ Changes Made:

🎨 Theme customization (new template design)
  
📊 Added user usage chart  

📊 Added per-location usage chart  

🧭 Display of days remaining next to the expiration date  

🔋 Estimated time for usage depletion  

📝 *Note: Some UI elements are still not fully translated. If you change the language, some parts may still remain in Persian. This will be fixed in future updates.*

---

## 📥 Installation & Setup

### 1️⃣ Download the Template File

```bash
sudo wget -N -P /var/lib/marzban/templates/subscription/ https://raw.githubusercontent.com/sarouk/Pro-Subscription-Template/main/index.html
```

### 2️⃣ Configure Marzban Environment

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"' | sudo tee -a /opt/marzban/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/marzban/.env
```

### 📝 Alternative Method: Add Directly to `.env` File

Open the `.env` file located at `/opt/marzban/` and add the following lines:

```bash
CUSTOM_TEMPLATES_DIRECTORY="/var/lib/marzban/templates/"
SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"
```

### 3️⃣ Restart Marzban

```bash
marzban restart
```

---

## 🔄 Update the Template

To get the latest version of the template, simply repeat **Step 1 (Download the Template File)**.

> Use code editors like VS Code to modify the HTML as needed. You can also utilize AI tools like Deepseek to conveniently customize different sections of the code to your liking.  
> Most of the modifications in this version were made using AI tools.

---

### 🛠 Key Line Modifications

| Line   | Description               |
|--------|---------------------------|
| 894    | Changed the logo          |
| 1750   | Changed the support link  |

---

<div align="center">
  <p>🌟 If you like this project, please give it a star 🌟</p>

  <p>
    <a href="https://github.com/sarouk/Pro-Subscription-Template">
      <img src="https://img.shields.io/github/stars/sarouk/Pro-Subscription-Template?style=social" alt="GitHub Stars">
    </a>
  </p>

  <img src="https://i.postimg.cc/xCdWMHhw/IMG-7600.gif" width="400"/>
</div>