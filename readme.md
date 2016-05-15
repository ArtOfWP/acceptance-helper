# Acceptance Testing Helper
I use this to help setup environment for when I run acceptance testing 
with different plugin setups.

## Usage

I make requests to these URLs duding my test suite setup method calls when I use JS based acceptance based test framework.

```
http://example.dev?activate_plugin=plugin/plugin-file.php,plugin2/plugin-file2.php
http://example.dev?deactivate_plugin=plugin/plugin-file.php,plugin2/plugin-file2.php
http://example.dev?activate_plugin=plugin/plugin-file.php?deactivate_plugin=plugin2/plugin-file2.php
```