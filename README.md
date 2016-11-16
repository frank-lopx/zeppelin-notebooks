# Zeppelin Notebooks
Web-based notebooks created with [Apache Zeppelin](https://zeppelin.apache.org/)

[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](https://opensource.org/licenses/MIT)

## Getting Started (in OS X)

1. Edit `/etc/hosts` adding your hostname: `127.0.0.1 localhost <hostname>`
2. Install Zeppelin: `brew install apache-zeppelin`
3. Start Zeppelin daemon: `./usr/local/Cellar/apache-zeppelin/0.6.2/bin/zeppelin-daemon.sh start`
4. Go to Zeppelin: `open http://localhost:8080`
5. Stop Zeppelin daemon: `./usr/local/Cellar/apache-zeppelin/0.6.2/bin/zeppelin-daemon.sh stop`

> For simplicity add aliases to your bash profile, for instance the following:
> `alias zep="/usr/local/Cellar/apache-zeppelin/0.6.2/bin/zeppelin-daemon.sh start && open http://localhost:8080"`
> `alias zepx="/usr/local/Cellar/apache-zeppelin/0.6.2/bin/zeppelin-daemon.sh stop"`
> `alias zepl="tail -f /usr/local/Cellar/apache-zeppelin/0.6.2/libexec/logs/zeppelin-interpreter-spark-username-hostname.log"`
> *Note: update 'username' and 'hostname' according to your system*



