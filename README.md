# hugotool - Basic Hugo post modification and management tool

hugotool is a POSIX shell script that allows some basic modifications to the
frontmatter section of Hugo posts. It does so in a **destructive** way, by
modifying the original file.

**Note:** This project is going to go through a major rewrite in the short term.
More details can be found in the project's [mailing list.][hugotool-devel-ml]

## Usage

To use hugotool just invoke the script as follows:

```shell
$ hugotool CMD FILE
```

Available commands follow:

* ``update:`` Update the date of a post to the current date.
* ``undraft:`` Remove draft status from a post.

## Contributing

Patches and discussion are welcome at the [hugotool-devel mailing
list][hugotool-devel-ml]. If you are not familiar with the Git email patch
workflow, [git-send-email.io][git-mail-web] is a great resource that walks you
through the basics. 

Subscribe to the [hugotool-announce mailing list][hugotool-announce-ml] for
announcements about releases and other critical milestones.

Tickets are tracked at the [hugotool tracker][hugotool-tracker].

You may find further information about this project at the [hugotool project
hub][hugotool-hub] as well.

## License

hugotool is licensed under the MIT License. See LICENSE file for copyright and 
license details.

[hugotool-devel-ml]: https://lists.sr.ht/~ariadna/hugotool-devel

[git-mail-web]: https://git-send-email.io/

[hugotool-announce-ml]: https://lists.sr.ht/~ariadna/hugotool-announce

[hugotool-tracker]: https://todo.sr.ht/~ariadna/hugotool

[hugotool-hub]: https://sr.ht/~ariadna/hugotool
