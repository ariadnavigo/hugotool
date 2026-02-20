# hugotool - Basic Hugo post modification and management tool

hugotool is a POSIX shell script that allows some basic modifications to the
frontmatter section of Hugo posts. It does so in a **destructive** way, by
modifying the original file.

## Usage

To use hugotool just invoke the script as follows:

```shell
$ hugotool CMD FILE
```

Available commands follow:

* ``update:`` Update the date of a post to the current date.
* ``undraft:`` Remove draft status from a post.

## Contributing

Patches and discussion are welcome at [my catch-all mailing list][pubinb-ml].
If you are not familiar with the Git email patch workflow,
[git-send-email.io][git-mail-web] is a great resource that walks you through the
basics. 

## License

hugotool is licensed under the MIT License. See LICENSE file for copyright and 
license details.

[pubinb-ml]: https://lists.sr.ht/~ariadna/public-inbox

[git-mail-web]: https://git-send-email.io/
