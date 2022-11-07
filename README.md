# Astrophysicists on Mastodon

[![Build and deploy](https://github.com/smaret/astrophysicists-on-mastodon/actions/workflows/jekyll.yml/badge.svg)](https://github.com/smaret/astrophysicists-on-mastodon/actions/workflows/jekyll.yml)

This repository provides a most simple web app that helps to bulk
follow astrophysicists on the FOSS microblogging service Mastodon. In it
you can create a csv file that can be uploaded in any accounts
mastodon seetings, in order to follow a list of accounts at once.

## Installation

```shell
gem install bundler
bundle install
bundle exec jekyll serve
```

## License

Code can be used under GNU General Public License v3, except
the `/resources/users.csv` file, which can only be used with
explicit permission by the authors.

## Credits

This repository is based on [Mastodon
Sociologists](https://github.com/trutzig89182/Mastodon-Sociologists).
