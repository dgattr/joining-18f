## Joining 18F

This is the repository for the [guide to joining 18F](https://pages.18f.gov/joining-18f/). This is an [18F Guide](https://github.com/18F/guides), built on the [18F Guides Template](https://github.com/18F/guides-template).

The application form itself lives in a separate repository: https://github.com/18F/joining-18f-app

### Send feedback

If you find something confusing or spot an error, please let us know by [filing an issue](https://github.com/18F/joining-18f/issues).

### Install and edit this guide on your computer

If you want to run your own copy of this guide, you'll need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). For complete instructions, see [18F Guides Template/README.md](https://github.com/18F/guides-template/blob/18f-pages/README.md)

#### Cloning and serving the guide locally

To serve this guide locally:

```shell
$ git clone git@github.com:18F/joining-18f.git
$ cd joining-18f
$ ./go serve
```

The `./go` script will check that your Ruby version is supported, install the [Bundler gem](http://bundler.io/) if it is not yet installed, install all the gems needed by the template, and launch a running instance on
`http://localhost:4000/`.

After going through these steps, run `./go` to see a list of available
commands. The `serve` command is the most common for routine development.

### Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
>All contributions to this project will be released under the CC0
>dedication. By submitting a pull request, you are agreeing to comply
>with this waiver of copyright interest.
