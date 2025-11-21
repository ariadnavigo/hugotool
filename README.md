# hugodateup - Update date on Hugo posts

hugodateup is a POSIX shell script that allows some modifications on Hugo posts
frontmatter: updating the publication date to the current date and removing
draft status from a post. It does so in a **destructive** way, by modifying the
original file.

## Usage

To use hugodateup just invoke the script as follows:

``$ hugodateup CMD FILE``

Available commands follow:

* ``dateup:`` Update a hugo post's date.
* ``undraft:`` Remove draft status from a post.

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
