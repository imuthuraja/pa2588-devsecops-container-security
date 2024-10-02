# DevSecOps-Lecture-Playground
Playground for Guestlectures about DevSecOps

  1. Fork this repository, and make sure to set the visibility to "Public".
  2. The GitHub actions should run automatically and be green.
  3. In `.github/workflows/docker-image.yml`, uncomment the block labeled "Version 1" to enable Trivy.
     After the next successful run of the GitHub actions, you should now see hundreds of security issues being reported.
  4. In `Dockerfile`, change the base image to the "slim" version.