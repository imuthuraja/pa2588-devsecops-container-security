# PA2588 DevSecOps: Playground for Container Security

This is part of the course DevSecOps.
You will cover two aspects of container security.

## Preparation

  1. Fork this repository, and make sure to set the visibility to "Public".
  2. The GitHub actions should run automatically and be green.

## 1. Scanning the Image

  3. In `.github/workflows/docker-image.yml`, uncomment the block labeled "Version 1" to enable Trivy.
     * After the next successful run of the GitHub actions, you should now see hundreds of security issues being reported.
  4. In `Dockerfile`, change the base image to the "slim" version.
     * After the next successful run of the GitHub actions, you should now see 90% of the security issues being closed.

## 2. Signing the Image

  5. In `.github/workflows/docker-image.yml`, uncomment the block labeled "Version 2" to enable Signing the Docker Image.
     * After the next successful run of the GitHib actions, you should now see that the built package is signed.
