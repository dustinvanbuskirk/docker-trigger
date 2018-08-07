# docker-trigger
Trigger Repository

- trigger 1
- trigger 2
- trigger 3
- trigger 4 adding no-cache to CLI
- trigger 5 removed no-cache from CLI added to Docker image build step in docker-builder Codefresh YAML
- trigger 6 additional trigger no changes, changes above resulted in complete docker image rebuild
- trigger 7 removing no_cache option from docker build step leaving cf_no_cache having both enabled rebuilds image from beginning
