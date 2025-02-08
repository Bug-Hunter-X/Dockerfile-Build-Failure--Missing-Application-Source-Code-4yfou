# Dockerfile Bug: Missing Application Source Code

This repository demonstrates a common error in Dockerfiles: forgetting to copy the application source code into the image.  The provided `Dockerfile` attempts to run a Python script (`main.py`), but the script isn't included in the image, leading to a build failure.

The `DockerfileFixed` file shows the corrected version, which includes copying the necessary files.