## queries

This repository contains SPARQL queries used to generate a [grlc](http://grlc.io/)-based Web API for [this](http://makingsense.liacs.nl/rdf4j-server/repositories/NC) RDF store.

**Prerequisites**
- [Docker Engine](https://docs.docker.com/engine/install/#server)
- [Docker Compose](https://docs.docker.com/compose/install/)

**Deploy**

`docker-compose up`

**Web API endpoint(s)**
- base URL `http://CNAME:PORT` (default: `http://localhost:8088`) followed by
- remote path `/api-git/LINNAE-project/queries/` or
- local path `/api-local/`
  - requires `docker cp queries grlc:/home/grlc/`
