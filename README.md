# ghost-aws-s3

A fork of [a fork](https://github.com/kimar/ghost-aws-s3) of [screenrev/ghost-s3](https://github.com/screenrev/ghost-s3) to allow [Ghost](https://github.com/TryGhost/Ghost) to store media using Amazon S3.

My fork adds compatibility with S3 for Ghost [v0.5.8](https://github.com/TryGhost/Ghost/releases/download/0.5.8/Ghost-0.5.8.zip).

See [http://blog.kida.io/ghost-on-heroku/](http://blog.kida.io/ghost-on-heroku/) for the original guide on how to integrate Ghost using Heroku and Amazon S3.

## Required dependencies

The following modules need to be installed as dependencies in order for this to work:

* [aws-sdk](https://www.npmjs.org/package/aws-sdk)
* [when](https://www.npmjs.org/package/when)

