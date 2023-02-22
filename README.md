# Get started with Cairo 1

Created from this [template]()

## Example

### Cairo-run

```terminal

```

### Cairo-test

```terminal

```

## Language server

To get proper syntax highlighting and code navigation in your editor, you will need the Cairo 1 extension.
You can find instructions on how to install the vscode extension [here](https://github.com/starkware-libs/cairo/blob/main/vscode-cairo/README.md).
You can build the language server manually by running `make language-server`, and then edit the configuration file of the extension to point to full path of the executable under `target/release/language-server`.
The language server needs the corelib/ directory to be present in the root directory of the project, hence it is copied from the cairo submodule when running `make install`.
