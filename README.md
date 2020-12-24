# `pinstall` 
A Perl script for installing scripts and manual pages on UNIX-like 
systems.

Document last updated 24nd December, 2020 (9 Tevet 5781);

### Table of Contents
- [About `pinstall`](#about-pinstall)
- [How to use `pinstall`](#how-to-use-pinstall)
- [Contributing](#contributing)
- [License](#license)

### About `pinstall`

`pinstall` is a short Perl script for installing scripts and manual 
pages on UNIX-like systems. It was created to compliment my personal
Perl scripts, allowing their painless deployment on different systems.

### How to use `pinstall`

1. Download the script and open it in your preferred text editor;
2. Update `srcfile` with the full name of the script that you wish to
install;
3. Update `binfile` with the command name that should run the script;
4. Update `manfile` with the full name of the accompanying manual file.

Full example:
```
my $srcfile = 'autoexec.pl';
my $binfile = 'autoexec';
my $manfile = 'autoexec.8';
```

If you do not wish to install a manual page, simply comment out all of
the lines that reference it.

### Contributing

Contributions can be made in the form of pull requests, or via bug 
reports and suggestions in the repository issues.

All contributors must assign the copyright of their contribution to the 
author of the project. This is to avoid the myraid of issues caused by 
having multiple intellectual property holders in a single project.

### License

Copyright &copy; 2020 Rachel Michaela Bradley.

`pinstall` is released in its entirety under the BSD 2-Clause License. 
The full text of this license is available in the COPYING file.