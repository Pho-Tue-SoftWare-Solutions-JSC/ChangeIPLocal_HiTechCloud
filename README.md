# 🌐 ChangeIPLocal_HITECHCLOUD

**ChangeIPLocal_HiTechCloud** is a Python-based tool designed to automate the process of updating local DNS records through the HITECHCLOUD API. This utility is particularly useful for users who need to programmatically manage their domain's DNS settings, such as updating A records to reflect changes in IP addresses.

---

## 🚀 Features

- ✅ **Automated DNS Updates**: Programmatically update A records for your domains hosted on 123HOST.
- 🔐 **Secure Authentication**: Utilizes API tokens to authenticate requests securely.
- 🛠️ **Configurable Settings**: Easily set your domain and API token within the script.
- 📦 **Lightweight and Efficient**: Minimal dependencies for quick setup and execution.

---

## 🛠️ Requirements

- **Python 3.6+**
- **Modules**: Listed in `requirements.txt`

Install the required modules using pip:

```bash
pip install -r requirements.txt
```

## 📥 Installation & Usage
# 1. Clone the Repository
```bash
git clone https://github.com/Pho-Tue-SoftWare-Solutions-JSC/ChangeIPLocal_HiTechCloud.git
cd ChangeIPLocal_HITECHCLOUD
```
# 2. Configure Your Settings
Open main.py and set your access_token and domain:
```bash
domain = "yourdomain.com"
```
# 3. Configure Your Settings
Execute the script to update your DNS records:
```bash
python main.py
```
The script will interact with the HITECHCLOUD API to update the A record for your specified domain.

## 📂 Project Structure
- **main.py**: Main script to execute the DNS update process.
- **API_HiTechCloud.py**: Contains functions to interact with the HiTechCloud API.
- **requirements.txt**: Lists the Python dependencies required for the project.

## 📄 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as per the license terms.

## 🙌 Acknowledgments
Developed by [HiTecgCloud](https://github.com/Pho-Tue-SoftWare-Solutions-JSC). Special thanks to the [HiTechCloud](https://hitechcloud.vn/) team for providing a robust API for DNS management.
