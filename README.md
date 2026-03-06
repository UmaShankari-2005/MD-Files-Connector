# 📄 MD-Files-Connector - Keep Markdown Files Linked Easily

[![Download MD-Files-Connector](https://img.shields.io/badge/Download-MD--Files--Connector-4caf50?style=for-the-badge)](https://github.com/UmaShankari-2005/MD-Files-Connector)

---

## 📝 What is MD-Files-Connector?

MD-Files-Connector is a simple tool designed to help you manage Markdown (.md) files in your project. It makes sure every Markdown file is linked from your main README file. This helps your documentation stay organized and easy to navigate.

The tool works by scanning all your Markdown files, sorting them, and fixing any that are not properly connected. If you use GitHub, MD-Files-Connector can run as part of your workflow to keep your docs clean automatically. It also provides a clear terminal dashboard so you can see the status at a glance.

## 📂 Key Features

- Scans all `.md` files in your project folder
- Checks if each file is linked from the root README
- Highlights any standalone (isolated) Markdown files
- Offers automatic fixes for isolated files
- Provides an easy-to-read terminal dashboard
- Works as a command-line interface (CLI) tool
- Integrates with GitHub Actions for automated checks
- Supports projects of any size and structure

## 🖥️ System Requirements

- Windows 7 or newer (Windows 10 recommended)
- Python 3.6 or above installed on your machine
- At least 100 MB free disk space
- Internet connection to download the tool and run updates

## 🚀 Getting Started

You do not need programming experience to use MD-Files-Connector. Follow these steps to download and start the tool.

## ⬇️ Download MD-Files-Connector

Click the link below to visit the GitHub page where you will find the latest version of MD-Files-Connector. From there, you can download the tool files:

[![Download MD-Files-Connector](https://img.shields.io/badge/Download-MD--Files--Connector-4caf50?style=for-the-badge)](https://github.com/UmaShankari-2005/MD-Files-Connector)

---

1. Open your web browser.
2. Go to the [MD-Files-Connector GitHub page](https://github.com/UmaShankari-2005/MD-Files-Connector).
3. Look for the "Releases" section or the "Download" option.
4. Download the ZIP file for the latest release.
5. Save the ZIP file to a known folder on your computer.

## 📂 Extract and Install

1. Locate the ZIP file on your computer.
2. Right-click the file and select "Extract All" or use any unzip tool you prefer.
3. Choose a folder to extract the files into, for example, `C:\MD-Files-Connector`.
4. After extraction, open that folder to find the program files.

## 🖱️ Running MD-Files-Connector on Windows

MD-Files-Connector uses the command line to run. Here is how you can start using it step by step:

1. Make sure Python 3 is installed on your Windows PC.
   - To check, open the Start menu, type "cmd", and press Enter.
   - In the command prompt window, type:
     ```
     python --version
     ```
   - If Python version 3.6 or higher appears, you are ready.
   - If not, download and install Python 3 from https://www.python.org/downloads/windows/.

2. Open the Command Prompt window:
   - Press the Windows key, type "cmd", and press Enter.

3. Change to the folder where you extracted the MD-Files-Connector:
   ```
   cd C:\MD-Files-Connector
   ```

4. Run the program by typing:
   ```
   python md_files_connector.py
   ```

5. Follow the on-screen instructions. The tool will scan your project folder for `.md` files and give you feedback.

## ⚙️ How to Use MD-Files-Connector for Your Project

MD-Files-Connector works best when you run it in the folder that contains your project files.

- Place your project folder anywhere on your computer.
- Open Command Prompt.
- Use the `cd` command to change to your project folder:
  ```
  cd path\to\your\project
  ```
- Run the MD-Files-Connector script by giving the full path or by adding its folder to your system PATH.

Example command:
```
python C:\MD-Files-Connector\md_files_connector.py
```

The tool will:

- Analyze `.md` files in your project.
- Notify you if any files are not linked from your main README.
- Offer to fix links automatically if you choose.

## 🖥️ Terminal Dashboard Explained

When you run the tool, it shows a dashboard with clear categories:

- Total `.md` files found
- Files linked from README
- Isolated files needing attention
- Suggested fixes available

You can use this dashboard to track your documentation coverage and quickly identify problems.

## 🔧 Settings and Customization

MD-Files-Connector allows some customization. You can:

- Set the name of your main README file if it’s not `README.md`.
- Choose whether to auto-fix isolated files or only receive warnings.
- Enable detailed logs for troubleshooting.

Settings can be changed in a simple config file named `config.yaml` found in the tool’s folder. If this file does not exist, the tool uses default settings.

Example config options:
```yaml
readme_file: README.md
auto_fix: true
verbose_logs: false
```

## ⚙️ GitHub Action Setup (Optional)

If you use GitHub for your projects, you can add the MD-Files-Connector as an automated check inside your workflow:

- The GitHub Action scans your `.md` files every time you push changes.
- It alerts you if documentation is missing links.
- This ensures your docs stay connected without manual checks.

To add this feature, visit the GitHub repository and look for the `GitHub Action` setup guide in the README file or documentation folder.

## 🛠️ Troubleshooting

- If the tool does not run, check that Python 3 is installed and the path is correct.
- If you encounter permission errors, try running Command Prompt as Administrator.
- Make sure your project folder actually contains `.md` files.
- For any errors, check the config file for typos or wrong settings.

## 📞 Support and Documentation

The GitHub page contains additional documentation, examples, and issue reporting. Use the "Issues" tab on the GitHub page to report problems or ask questions.

Link to visit for support and updates:

[https://github.com/UmaShankari-2005/MD-Files-Connector](https://github.com/UmaShankari-2005/MD-Files-Connector)

## 🔑 Topics Covered

This tool is useful for:

- Automating documentation checks
- Improving code quality with better docs
- Using easy CLI tools without coding skills
- Managing Markdown files and README links
- Integrating with developer workflows

---

[![Download MD-Files-Connector](https://img.shields.io/badge/Download-MD--Files--Connector-4caf50?style=for-the-badge)](https://github.com/UmaShankari-2005/MD-Files-Connector)