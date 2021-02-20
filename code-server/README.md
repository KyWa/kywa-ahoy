# Code-Server Helm Chart

Image used is built fromn [this](https://github.com/KyWa/dockerbuilds/tree/master/code-server) repo. 

## TODO

* Secure ENV for password (or autogenerate and require looking at logs)
* create deploy parent object to generate template from in `values.yaml`
* update deployment for persistent storage (current ephimeral)
