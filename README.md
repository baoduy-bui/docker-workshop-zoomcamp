# docker-workshop-zoomcamp
Workshop from De Zoomcamp

Note: 

- using UV --dev for adding lib when only need that lib for dev
- using click with uv python for adding parameters
- for connect the container taxi_ingest:v001 with the pg containter, we need to create a netwoek via:
    `docker network create pg-network`