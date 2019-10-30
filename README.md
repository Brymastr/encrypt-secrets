## NOTE:

- openssl v1.1.1b or newer is required specifically for the `-pbkdf2` flag
- MacOS comes with LibreSSL which is not fully compatible
- Install on MacOS with `brew install openssl@1.1`
- Windows requires glhf

## gitignore

please add this to your gitignore `**/secret*.y*ml`
This will ignore all files that look like `secrets/secret.yml` or `deployment/app/nginx/secrets.yml`
