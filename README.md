# AmPower OrderIT App

AmPower OrderIT App is a **Frappe application** that provides configuration options to enable or disable the AmPower OrderIT Mobile App within your ERP system.

---

## 🚀 Features

- Simple checkbox to **Enable/Disable OrderIT App**.
- Configuration managed through a dedicated doctype.
- Easy to install and integrate with existing Frappe/ERPNext setups.

---

## ⚙️ Configuration

The app includes a configuration doctype:

**Doctype Name:** `OrderIT Community Config`

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
