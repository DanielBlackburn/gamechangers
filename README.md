# Gamechangers Aalto web app.

This is the web app for the Aalto Gamechangers project.
https://gamechangers.aalto.fi


# Prerequisites

Polymer - https://www.polymer-project.org/1.0/

    npm install -g polymer-cli

Deepamehta http://www.deepamehta.de/


# Start the development server

Make sure the lcoal Deepamehta instance is running at `http://localhost:8080`
and has the gamechangers  (https://github.com/digitalmemex/dm4-gamechangers)
plugin installed

Then use this command to serve the app at `http://localhost:8181` and open
it in a browser.

    polymer serve -p 8181 -o


# Build

This command generates `build/unbundled` for serving from a HTTP/2+Push
compatible server and `build/bundled` for serving from non H2/push-compatible
servers or to clients that do not support H2/Push.

    polymer build
