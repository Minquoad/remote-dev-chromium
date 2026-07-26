# Remote Development Chromium

This repository runs a shared Chromium browser in Docker so both a human developer over the Selkies web UI and a CLI AI agnet through Chrome remote debugging can use the same browser session.

The web UI is exposed over HTTPS on port `6080`, while the debugging endpoint is bound locally on `127.0.0.1:9222`.
