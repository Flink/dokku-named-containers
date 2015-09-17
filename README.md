# dokku-named-containers

dokku-named-containers is a plugin for [dokku][dokku] that names docker containers after your application name.

## Installation

```sh
$ sudo git clone https://github.com/Flink/dokku-named-containers.git /var/lib/dokku/plugins/named-containers
```

## Usage

There’s nothing to do or configure after installing this plugin. Just start or restart your applications and their docker container will now be named like this:
```
app-name.web.1
app-name.web.2
app-name.worker.1
```

This is useful when sending logs with logspout to Papertrail for example.

## License

This plugin is released under the MIT license. See the file [LICENSE](LICENSE).

[dokku]: https://github.com/progrium/dokku
