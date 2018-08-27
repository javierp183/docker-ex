# docker-ex

The following docker technology mix, performs the orchestration of "prometheus,wordpress & Grafana" via Docker-Compose. It includes make files for image creation/customization and DockerFile for each one.

* Technical instructions: First of all, clone "GIT" repo: #git clone https://github.com/javierp183/docker-ex.git

* Generate docker images

* #cd Grafana ; make image; make publish
* #cd WordPress ; make image; make publish
* #cd prometheus ; make image; make publish

* Run Docker compose:
* #docker-compose -f compose.yml up
