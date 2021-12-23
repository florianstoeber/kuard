1. Pull des Repos
2. Alle drei binaries bauen: make all-fakever-build
3. Alle drei docker image bauen: docker build -f Dockerfile.color -t name:color .
4. Run webserver und test
5. Taggen der Binary auf acr:/name:blue acr:/name:green acr:/name:purple
6. pushen nach acr