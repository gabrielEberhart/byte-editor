# Byte Editor

A terminal-based editor for files which do not support text encoding.

## Features

| Feature | Status | Note |
|:------- |:------:|:---- |
| Vim motions | X | WIP |
| Side-by-side comparison | X | WIP |

## Usage

Run src/main.py to begin the editor. I recommend setting up a symbolic link to
make it easier to run from the command line, eg `./byte-editor`.

Comes with several parameters to customize the editor's behavior.

Runs with approximately `./byte-editor <FILE1>`.

For a full list of options, run the script with `--help`.

For information on input keymappings when viewing a file, refer to docs/keymappings.md.
