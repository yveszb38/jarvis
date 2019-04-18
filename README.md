<div align="center">
    <img src="./logo.png" />
</div>

## 📋 Requirements:
These are the required libraries/packages to run this stack:
 - [Docker](https://docker.com)
 - [Docker Compose](https://docs.docker.com/compose/)

## ⬇️ Installation:
```shell
git clone https://github.com/NuroDev/jarvis.git
```
```shell
cd jarvis/
```

## 🔧 Configure:
Sadly there are some things that need to be configured to get Jarvis up and running. Some containers do require some extra setup to get up and running as well as setting up your `.env` config. All documentation for this can be found [here](https://github.com/NuroDev/jarvis/blob/master/config.md)

## 🚀 Usage:
```
docker-compose up -d
```

## 🔑 Access:
| Container		| Description                | URL                    | Port        |
| ------------- |:--------------------------:|:----------------------:|:-----------:|
| Cadvisor		| Docker Metrics             | `cadvisor.ip_address`  | `8074`      |
| Grafana		| Monitoring Dashboard       | `monitoring.ip_address`| `8075`      |
| Heimdall		| Stack Manager              | `manager.ip_address`   | `8076`      |
| Influx		| Database                   | `db.ip_address`        | `8077`      |
| Ombi			| Content Requesting         | `request.ip_address`   | `8078`      |
| Plex      	| Content Streaming          | `plex.ip_address`      | `32400`     |
| Tautulli      | Plex Metrics               | `tautulli.ip_address`  | `8079`      |
| Traefik       | Reverse Proxy              | `proxy.ip_address`     | `8080`      |

## 📄 License:
MIT © [Ben Dixon](https://github.com/NuroDev/jarvis/blob/master/LICENSE)
