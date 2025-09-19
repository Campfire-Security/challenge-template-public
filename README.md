# challenge-template-public
This is a challenge template used for developing challenges for our CTF platform.

The template is currently providing af base for a DYNAMIC challenge. When creating containers for a dynamic challenge you need to tag them correctly in your `docker-compose.yml` file.  
For dynamic challenges using a single container use
* `ghcr.io/campfire-security/<repo-path>`  

For dynamic challenges using multiple containers use
* `ghcr.io/campfire-security/<repo-path>:container-tag`

If you wish to do a STATIC challenge ie. no containers. feel free to remove the `Dockerfile` and `docker-compose.yml` file.
You will also need to set the `static` variable in the challenge.yml file to `false`
