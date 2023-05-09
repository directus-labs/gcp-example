<img src=".github/community-maintained.svg" width="100%" alt="Community-maintained. This project is not maintained by the Directus Core Team, but by our wider community. Interested in taking it on? Get in touch!">

# Run Directus in a Cloud Run container.

This repo just demonstrates how [Cloud Run](https://cloud.google.com/run) can run [Directus](https://directus.io/).

Keep in mind, this will use a non persistent SQLite database inside the container itself, so everything will be lost once the container shuts down. And it will shut down.

[![Run Directus in Google Cloud Run](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run/)

After deploying you can login with `admin@example.com` and `localpassword`

More info in proper deployment can be found in the [Directus documentation](https://docs.directus.io/getting-started/installation/gcp/).

