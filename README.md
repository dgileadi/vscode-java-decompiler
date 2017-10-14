# Decompiler for Java&trade; in Visual Studio Code

This extension allows you to decompile Java class files. It requires [Language Support for Java&trade; by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java), version 0.12.0 or greater.

To see the decompiler in action, right-click on a Java symbol for which you don't have the source code, and choose Go to Definition (or simply command/ctrl+click on the symbol). You will see the decompiled code.

## Requirements

[Language Support for Java&trade; by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java), version 0.12.0 or greater. This extension does not work with older versions.

## Extension Settings

You can use the following settings to customize the decompiler:

* `java.contentProvider.preferred`: the ID of a decompiler to use. Currently, `fernflower`, `cfr` and `procyon` are supported. Defaults to `fernflower`.
* `java.decompiler.[id]` (replace `[id]` with the ID of the decompiler you wish to configure): additional configuration to provide to the decompiler. The format depends on the chosen decompiler. Use the autocomplete functionality of Visual Studio Code's settings to view the possible options and their descriptions.
