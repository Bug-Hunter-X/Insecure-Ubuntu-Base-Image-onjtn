This repository demonstrates a common mistake in Dockerfiles: using the `latest` tag for base images.  The `latest` tag is inherently unstable, meaning that the image's contents can change unexpectedly between builds, breaking your application. This can lead to inconsistent builds and deployment issues.  The provided solution shows how to specify a concrete version for increased reproducibility and stability.