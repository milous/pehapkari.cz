# Pehapkari.cz - [Statie](https://github.com/Symplify/Statie) based web

[![Chat on Slack](https://img.shields.io/badge/Slack-960+-green.svg?style=flat-square)](https://pehapkari.cz/#slack)
[![Build Status](https://img.shields.io/travis/pehapkari/pehapkari.cz/master.svg?style=flat-square)](https://travis-ci.org/pehapkari/pehapkari.cz)
[![Code Coverage](https://img.shields.io/scrutinizer/coverage/g/pehapkari/pehapkari.cz.svg?style=flat-square)](https://scrutinizer-ci.com/g/pehapkari/pehapkari.cz)


## Install

```sh
composer create-project pehapkari/website pehapkari.cz @dev
```

To enabled live reload after any change, we need one more thing - *gulp*:

```bash
npm install -g gulp gulp-watch
```

## Run the website

Now all you gotta do it move to the directory and run the gulp (see [gulpfile.js](/gulpfile.js) for more details):

```sh
cd pehapkari.cz
composer update
npm install
gulp
```

And open [http://localhost:8000](http://localhost:8000) in your browser.

That's all!


### Docker Enabled

Are you using Docker? [Here is how to run this project](docs/docker.md) in it.
