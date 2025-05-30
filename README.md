# hugodateup - Update date on Hugo posts

hugodateup is a POSIX shell script that updates the date on a Hugo post
frontmatter to the current date. It does so in a **destructive** way, by
modifying the original file.

## Usage

To use hugodateup just invoke the script as follows:

``$ hugodateup FILE``

## Known issues

This script is written for POSIX shell, but requires the use of the GNU 
coreutils version of ``date(1)``, or, alternatively, an implementation thereof
that supports the ``-I`` flag as implemented by GNU. Standard compliance is a
goal, so we hope this can be fixed accordingly.

Currently, hugodateup is only able to modify Hugo post files whose frontmatter 
is formatted in TOML. YAML support is pending.

## License

hugodateup is licensed under the MIT License. See LICENSE file for copyright and 
license details.
