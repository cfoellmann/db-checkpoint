# wp-cli db-checkpoint

WP-CLI command for quick db snapshots. Currently supported commands:

* `wp dbsnap` -- Create a db snapshot.
* `wp dbsnapback` -- Restore a db snapshot.
* `wp dbsnap test` -- Create a db snapshot of a specific name.
* `wp dbsnapback test` -- Restore a db snapshot of specific name.

## Why doesn't this do _x_?

Because I haven't built it yet. I'm filling in commands as I need them, which means that they are largely developer-focused. I'll fill in more commands as I need them. Pull requests will be enthusiastically received.

## System Requirements

* PHP >=5.3

## Setup

* Install [wp-cli](https://wp-cli.org)
* Install this package with this command: `wp package install binarygary/db-checkpoint`
* Inside of a WP installation, type `wp`. You should see a list of available commands.

## Changelog

### 0.2.2 ###
* Adds flag --dev which prompts.

### 0.2.1 ###
* Adds flag --dumplog which removes the debug.log file.

### 0.2.0

* Added a method to install the helper plugin.
* Helper plugin adds a restore option to the admin bar.

### 0.1.0

* Initial release
