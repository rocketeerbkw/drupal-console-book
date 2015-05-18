# config:edit
The **config:edit** command allows editing the selected configuration

```
$ drupal config:edit --help
```
**Usage:**
```
config:edit config-name [editor]
```
## Arguments
Argument | Details
------------ |-------------
config-name     |      Configuration name.
editor         |      Editor.


## Available options
Options | Details
------------ |-------------
--help (-h)     |       Display this help message
--quiet (-q)     |      Do not output any message
**--verbose** (-v) | Show more verbose messages
--vv | Increase the verbosity of messages
--vvv | Debug mode verbosity
--version (-V)    |     Display this application version
--ansi             |    Force ANSI output
--no-ansi          |    Disable ANSI output
--no-interaction (-n)  | Do not ask any interactive question
--drupal (-d)      |    Path to Drupal root.
--shell (-s)       |    Launch the shell.
--env (-e)         |    The Environment name. (default: "prod")
--no-debug         |    Switches off debug mode.
--learning         |    Generate a verbose code output.