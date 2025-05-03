[简体中文](README.md) | [English](README_EN.md)

<div style="display: flex; justify-content: space-between;">
    <img src="https://img.shields.io/github/commit-activity/w/Aurora-Nasa-1/AMMF" alt="GitHub Commit" style="margin-right: 10px;">
    <img src="https://img.shields.io/github/license/Aurora-Nasa-1/AMMF" alt="GitHub License">
</div>

**New Version: [AMMF2](https://github.com/Aurora-Nasa-1/AMMF2)**

**[Telegram](https://t.me/AuroraNasaModule)**

# 🚀 Quick Start

Welcome to use this module framework! Here are the steps to get started:

## 📥 Get the Framework

- **Fork** this repository or **download** this repository directly.

## ⚙️ Configuration Settings

1. Edit the `./settings/Settings.sh` file:
   - Write your module name and module description.
   - Specify the environment required by the module.

2. Edit the `./settings/languages.ini` file to enable multi-language support.

## 🛠️ Custom Scripts

- **Do not use** `custmize.sh` as the custom installation script.
- You should choose `./settings/custom_script.sh` as the custom script.
- This framework provides some functions, please read the [instructions](SCRIPT_EN.md).

## 🌐 Custom WebUI

- WebUI allows users to easily configure the values of variables in `settings.sh`.
- See [WebUI User Guide](WEBUI_GUIDE_EN.md) for more information.

## 🖱️ User Scripts

- `Click.sh` can be used by users to execute scripts provided by the module outside the module.
- `Click.sh` uses `busybox` to execute `./settings/script/custom_script_user.sh` in `/data/local/tmp/`.
- This framework provides some functions, please read the [instructions](SCRIPT_EN.md).

## 🏗️ Framework Applicability

- This framework is suitable for **GitHub Action** to package modules.
- This framework removes `META-INF` by default, please add it yourself if needed.

## 📝 Update Notes

- For future updates to the module framework, please check the [Update Notes](CHANGELOG.md).

---

PRs are welcome. If you find it useful, please give it a star. Thank you for using this framework! 🚀

(Extracted and modified from AuroraNasa_Installer, please don't criticize if you don't like it)
