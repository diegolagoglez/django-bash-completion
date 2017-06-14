# Django BASH autocompletion

## Introduction

[Django](https://www.djangoproject.com) has a [contributed script to allow BASH autocompletion](https://github.com/django/django/blob/master/extras/django_bash_completion). This script runs `manage.py` every time the user press Tab key to view completion options, which leads to a really slow completion feature.

With this new script, a statically generated BASH source with all `manage.py` avalible commands and options is used, which leads to a much faster completion feature.

This script is still under development, so some features are missing and it may misbehave. Please, [file issues](https://github.com/diegolagoglez/django-bash-completion/issues) if you find any error or misbehaviour.

## Load

In order to load this autocompletion script, simply run next command:

```bash
user@workstation ~/projects/django-bash-completion $ source django-bash-completion
```

## How to update statically generated BASH source

TBD

## Author & License

[GPLv3](http://www.gnu.org/licenses/gpl.html) — [Diego Lago](mailto:diego.lago.gonzalez@gmail.com)
