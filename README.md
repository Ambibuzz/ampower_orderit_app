# AmPower OrderIT App

AmPower OrderIT App is a **Frappe application** that provides configuration options to enable or disable the AmPower OrderIT Mobile App within your ERP system.

This app acts as a **wrapper for the AmPower OrderIT Mobile App**, enabling you to manage its availability and integration from within your ERP instance.

---

## 🚀 Features

- Simple checkbox to **Enable/Disable OrderIT App**.
- Configuration managed through a dedicated doctype.
- Easy to install and integrate with existing Frappe/ERPNext setups.

---

## 🔗 Mobile App Features

👉 You can explore the detailed features of the OrderIT App in our mobile app repository:  
[AmPower OrderIT Mobile App](https://github.com/Ambibuzz/ampower_orderit_mobile_app)

### Short Summary of Features

**The OrderIT App simplifies B2B ordering with flexible product views, customer-specific pricing, real-time stock visibility, and seamless order management. It also offers role-based access, personalized features like wishlist and favorites, and easy sharing of sales orders.**

---


## ⚙️ Configuration

The app includes a configuration doctype:

**Doctype Name:** `Ampower Orderit App`

**Enable OrderIT** → *(Checkbox)*  
  When checked, the OrderIT App is enabled.  
  When unchecked, the OrderIT App is disabled.

---

## 📦 Installation

1. Navigate to your Frappe/ERPNext bench folder:

```bash
# Navigate to your Frappe bench directory
cd ~/frappe-bench

# Get the app
bench get-app https://github.com/Ambibuzz/ampower_orderit_app

# Install the app on your site
bench --site your-site-name install-app ampower_orderit_app
```

---
## 📄 License

MIT License
