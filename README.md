# easyUML 1.7.12

Prebuilt easyUML plugin for NetBeans, providing UML class diagrams, Java code
generation and reverse engineering. The plugin is distributed as a single
`easyuml.nbm` with its required libraries bundled.

[Source code](https://github.com/Bin-2/easyuml)

## Compatibility

- **Target IDEs:** NetBeans 8.2 and newer.
- **Plugin minimum:** Java 8. Run NetBeans with a JDK supported by that IDE version.

The plugin is compiled with the NetBeans >= 8.2 APIs.

## Installation

1. Open **Tools > Plugins > Settings** in NetBeans.
2. Click **Add** and enter a name such as `easyUML Update Center`.
3. Set the update-center URL to:

   ```text
   https://raw.githubusercontent.com/Bin-2/easyuml-update/main/updates.xml
   ```

4. Open **Available Plugins**, refresh the list if needed, and select **easyUML**.
   For an existing installation, check the **Updates** tab.
5. Complete installation and restart NetBeans when prompted.

To install a downloaded package directly, use **Tools > Plugins > Downloaded >
Add Plugins**, select `easyuml.nbm`, and complete the installation and restart.

## Upgrading an older installation

For profile-local installations of the ten-module releases 1.4, 1.5, 1.6 and
1.7, the bundled updater removes the obsolete easyUML modules during restart.
Existing UML projects, diagrams and the saved Explorer layout are preserved.

If an upgrade reports a migration failure, see `var/easyuml/nbm-upgrade.log` in
the NetBeans user directory shown under **Help > About**.

## Release contents

- `updates.xml` — NetBeans Update Center catalog.
- `easyuml.nbm` — the complete easyUML plugin, including required libraries.

## Main changes

- **Simpler installation:** one NBM, with automatic migration from the legacy
  module packages and preservation of the Explorer layout.
- **Improved display and export:** scalable icons, PNG/SVG/PDF output.
