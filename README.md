# SLSA workflow for testing

Find here : https://github.com/dn-org/slsa a public repo with a simple workflow for experimenting with the github app.

The worflow creates a docker image + gensboms it and uploads to Scribe + creates Provenance + creates a local copy of the slsa report for debugging.

Usage:

* Fork the repo and create your secrets.
* Secrets needed are the ScribeHub triplet + a GH Token you need to create with repo permissions (the automatic GH_TOKEN will not do.

