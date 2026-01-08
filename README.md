# ESPHome

ESPHome YAML configuration file syntax.

See [ESPHome YAML configuration documentation](https://esphome.io/guides/yaml/).

## Usage

To apply the syntax, select `YAML (esphome)` from the Command Palette or from the syntax selector in the status bar.

Since ESPHome configuration files use the `.yml`/`.yaml` extension and do not differ much from standard YAML files, there is no easy way to automatically assign a specific syntax to all ESPHome configuration files (unless you want to use this syntax for all YAML files, which could introduce its own problems). Therefore, it is recommended to use the [ApplySyntax](https://packages.sublimetext.io/packages/ApplySyntax) or [AutoSetSyntax](https://packages.sublimetext.io/packages/AutoSetSyntax) package to assign this syntax based on the file path - most likely on a per-project basis since there is nothing inherently unique about the file names or paths of these configuration files.
