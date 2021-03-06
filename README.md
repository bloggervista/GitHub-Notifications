GitHub Notifications
====================

GitHub Notifications was created by, and is maintained by [Graham Campbell](https://github.com/GrahamCampbell), and is a simple command line tool to mark all issue notifications as read on a given organization. Feel free to check out the [releases](https://github.com/GrahamCampbell/GitHub-Notificationsreleases) and [license](LICENSE.md).


## Installation

This project is relatively small, and it's usage is pretty simple. [PHP](https://php.net) 7.1.3+ is required.

To get the latest version, simply require the project using [Composer](https://getcomposer.org):

```bash
$ composer global require graham-campbell/github-notifications
```


## Usage

By default, we'll try and read your personal access token for GitHub from the `GITHUB_TOKEN` environment variable, however you can also specify a token with the `--token` command-line flag.

To clear all issue notifications for the Laravel organization:

```bash
$ notifications clear laravel
```

Or, if you are specifying a token:

```bash
$ notifications clear laravel --token {...}
```


## Security

If you discover a security vulnerability within this package, please send an e-mail to Graham Campbell at graham@alt-three.com. All security vulnerabilities will be promptly addressed.


## License

GitHub Notifications is licensed under [The MIT License (MIT)](LICENSE).
