Demo: Kafka & Spark Streaming
===

(Note: Only Tested on Mac OS X Yosemite so far)

The following must be installed on your machine:

* Docker
* Docker-compose

After the above are installed and cloning this git repository, running the following command in your shell/terminal 
will launch several Docker containers based on the docker-compose.yml configuration file:

```
bash-3.2$ docker-compose up
```

You may see errors and, thus, may need to try again a few times due to the nondeterministic nature of the startup order 
of the individual containers...
