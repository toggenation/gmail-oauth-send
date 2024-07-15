# CakePHP 5 Application with GmailEmailSend Plugin

This CakePHP 5 Application is pretty much empty but references a git submodule `plugins/GmailEmailSend` a CakePHP  Plugin that includes the ability to authenticate as a Google User with the GMail API and send emails

plugins/GmailEmailSend is located => https://github.com/toggenation/gmail-email-send.git

See the README.md for the GmailEmailSend plugin for more information on running it.

Clone this repo then pull in `plugins/GmailEmailSend` using

```sh
cd $project_root
git submodule update --init --recursive
composer install
```