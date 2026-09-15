Prebuilt easyUML modules for Apache NetBeans 24 / JDK 21 (installable for later versions).

This repository contains the `.nbm` packages and `updates.xml` catalog required to install and update easyUML directly from NetBeans.

Source code: https://github.com/Bin-2/easyuml

## Installation

1. Open **NetBeans ? Tools ? Plugins ? Settings**.
2. Click **Add**.
3. Enter a name such as `easyUML Update Center`.
4. Set the URL to the public URL of this repository's `updates.xml`.
     ```
     https://raw.githubusercontent.com/Bin-2/easyuml-update/main/updates.xml
     ```
5. Open the **Available Plugins** tab.
6. Search for **easyUML** and install it.

NetBeans will automatically resolve and install the required easyUML modules.

## Contents

- `updates.xml` — NetBeans Update Center catalog
- `easyuml.nbm` — main easyUML plugin
- supporting `.nbm` modules required by easyUML# easyuml-update

