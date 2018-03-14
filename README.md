# Keycloal, JavaScript, API Sample

Demonstrates a simple index.html that redirects to local keycloak server in case the user is not logged in. Keycloak returns a signed JWT on successful login. The token can be used to authorize client requests against an API.

## Setup

Start the API

Start keycloak: /usr/local/keycloak-3.4.3.Final/bin/standalone.sh

Start web app: python -m SimpleHTTPServer 800

Open http://localhost:8000 in your browser

