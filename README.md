# NMAP
NMAP ("Network Mapper") is a FOSS utility for network discovery and security auditing.

## NMAP (Project Info)
[Website](https://nmap.org/)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/nmap/)

## Build image
`$ docker build -t macabees/nmap:latest .`

## Docker Push
`$ docker push -t macabees/nmap:latest`

Note: requires `docker login`

## Run image
`$ docker run -it --rm macabees/nmap -v scanme.nmap.org`

## Help
`$ docker run -it --rm macabees/nmap --help`
