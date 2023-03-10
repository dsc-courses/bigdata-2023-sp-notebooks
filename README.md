=== Configuring different environments

We currently have three deployments for spark. 
1. Using Docker
2. On Vocareum
3. on DataHub

the file `environ.yaml` contains the currently active deplyment parameters.;

This file is replaced by environ_docker.yaml, environ_vocareum.yaml or environ_datahub.yaml

THe idfea is that the public repository is cloned  and then the configuration is set to the correct one, everything should work from there.
