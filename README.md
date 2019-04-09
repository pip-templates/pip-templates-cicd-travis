# travis-ci.org settings

Required environment variables:
* **DOCKER_USER** - docker username to access docker registry on image publish
* **DOCKER_PASS** - docker password to access docker registry on image publish
* **GIT_EMAIL** - git user email to access git repository and publish tag
* **GIT_PRIVATE_KEY** - base64 encoded content of id_rsa in single line
* **GIT_USER** - git username to access git repository and publish tag
* **GITHUB_API_KEY** - git user access token to pubsh
* **NPM_TOKEN** - token set to .npmrc to access npm registry on release.ps1