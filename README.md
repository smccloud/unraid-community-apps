# Unraid Community Applications — smccloud

A repository of Docker container templates maintained by **smccloud** for the [Unraid Community Applications](https://unraid.net) catalog.

---

## 📦 Available Templates

| Application | Category | Description | Template |
| :--- | :--- | :--- | :--- |
| **UniFi WiFi Access Manager** | `Network` | Application to allow you to allow and block access to your UniFi Wifi network on a schedule. | [`templates/unifi-wifi-tool.xml`](templates/unifi-wifi-tool.xml) |

---

## 🚀 Installation

### Option 1: Via Community Applications (Recommended)
1. Open your Unraid WebGUI and navigate to the **Apps** tab.
2. Search for the application name in the Community Applications search bar.
3. Click **Install**, review your port mappings, volume paths (`/mnt/user/appdata/...`), and environment variables, then click **Apply**.

### Option 2: Manual Template URL
If an application is not yet indexed in Community Applications, you can load the template directly:
1. Open your Unraid WebGUI and go to **Docker** > **Add Container**.
2. Copy the raw GitHub URL of the desired `.xml` file from the [`templates/`](templates/) directory (e.g., `https://githubusercontent.com<app-name>.xml`).
3. Paste it into the **Template** field or save it locally to `/boot/config/plugins/dockerMan/templates-user/`.

---

## 🛠️ Support & Issues

* **Template & Unraid Configuration Issues:** Please open an [Issue](https://github.com) in this repository or post in the corresponding [Unraid Forums](https://unraid.net) support thread linked inside each template's `<Support>` tag.
* **Upstream Application Bugs:** For bugs or feature requests unrelated to the Unraid template itself, please report them directly to the upstream project repository.

---

## 📄 License

This repository and its templates are licensed under the [MIT License](LICENSE).
