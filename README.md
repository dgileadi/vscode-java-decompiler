# Decompiler for Java &trade; in Visual Studio Code

This extension allows you to decompile java class files. It requires [Language Support for Java &trade; by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java), version 1.11.0 or greater.

To see the decompiler in action, right-click on a Java symbol for which you don't have the source code, and choose Go to Definition (or simply command/ctrl+click on the symbol). You will see the decompiled code.

## Requirements

[Language Support for Java &trade; by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java), version 1.11.0 or greater. This extension does not work with older versions.

## Extension Settings

You can use the following settings to customize the decompiler:

* `java.decompiler.id`: the ID of a decompiler to use. Currently only `fernflower` is supported.
* `java.decompiler.configuration`: additional configuration to provide to the decompiler. The format depends on the chosen decompiler, and is typically in the form of the decompiler's command-line options.
    * [Fernflower's command-line options](https://github.com/JetBrains/intellij-community/tree/master/plugins/java-decompiler/engine#command-line-options)
