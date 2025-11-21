# hugotool - Basic Hugo post modification tool

hugotool is a POSIX shell script that allows some basic modifications to the
frontmatter section of Hugo posts. It does so in a **destructive** way, by
modifying the original file.

## Usage

To use hugotool just invoke the script as follows:

``$ hugotool CMD FILE``

Available commands follow:

* ``dateup:`` Update the date of a post to the current date.
* ``undraft:`` Remove draft status from a post.

## Known issues

This script is written for POSIX shell, but requires the use of the GNU 
coreutils version of ``date(1)``, or, alternatively, an implementation thereof
that supports the ``-I`` flag as implemented by GNU. Standard compliance is a
goal, so we hope this can be fixed accordingly.

Currently, hugotool is only able to modify Hugo post files whose frontmatter 
is formatted in TOML. YAML support is pending.

## License

hugotool is licensed under the MIT License. See LICENSE file for copyright and 
license details.
