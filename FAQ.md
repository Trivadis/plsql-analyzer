# Frequently Asked Questions

## I get the error "Could not reserve enough space for …KB object heap". What’s wrong?

You are probably using a 32-bit Java version and trying to configure more than 1GB of heap space, e.g. `-Xmx2048m`.

Define either `-Xmx1024m` or use a 64-bit Java version.

## I get the error "The system cannot find the path specified". What’s wrong?

Check if you have defined the correct `JAVA_HOME` environment variable in the .cmd/.sh file.

On Windows the `java.exe` is located in the `%JAVA_HOME%\bin` directory.

## What are the limitations?

See [parser limitations](https://github.com/Trivadis/plsql-cop-cli/blob/master/parser-limitations.md).

## What has changed in the latest version?

See the [release information](https://github.com/Trivadis/plsql-analyzer/releases) for each version.

## What are the licensing terms?

The preview/trial version of PL/SQL Analyzer is licensed under the Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License. You may obtain a copy of the License at https://creativecommons.org/licenses/by-nc-nd/3.0/.

![CC-BY_NC-ND](images/CC-BY-NC-ND.png)

The trial/preview version provides full functionality but is limited in time and volume.

For production use a separate software license agreement is required.
