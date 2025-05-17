<div
  align="center"
  style="font-weight: 600;">
  <image
    src="./images/logo.png"
    alt="Logo"
    width="650"
    height="250">
  <P
    style="font-size: 24px;"
  >
    A tool for creating none compiled Debian packages.
  </P>
</div>

When building a Debian package for a standard binary or interpreted scripting language there needs to be a set way to go about it. This is where this tool comes in. It is a simple command line tool that will create a Debian package for you. It will take care of all the details and make sure that the package is built correctly.

## Features

- Generates the basic directories structure.
- Create the required files for the package.
- Test the package after it is built.

## Usage

Using **DPKG-CRAFT** is simple and straightforward.

```console
Usage: dpkg-craft [COMMAND] [OPTIONS] [ARGS] ...

Commands:
  configure       Configure the package; for more details use --help.

  build           Build the package; for more details use --help.

  test            Test the package; for more details use --help.

  clean           Clean the package; for more details use --help.

  help            Show this message and exit.

  version         Show the version and exit.

Options:
  --help           Show options for given commands.

```

## To Do List

- [x] Add help/version
- [ ] Add configuration functionality.
- [ ] Add build functionality.
- [ ] Add test functionality.
- [ ] Add clean functionality.
- [ ] Add logging functionality.
- [ ] Add error handling.

For each main function, documentation will be added.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

- Michael Lee Schaecher \<MichaelLeeSchaecher@gmail.com\>

## License

This project is licensed under the GPL-3.0 License - see the [COPYING](COPYING) file for details.
