# Foxhole configs

This repository is used to manage configs for our competitive CS:GO server.

* Get5 match configs reside in `addons/sourcemod/get5`.
* The live Get5 config is `cfg/get5/live.cfg`.
* Other live configs are found in `cfg/`.

## Automated deployment

This repository mirrors the configuration files on the CS:GO
server. Any change made to a configuration file in this repository
will be automatically reflected on the CS:GO server via the automated
deployment script. Thus to submit a change simply edit the file via
the GitHub interface or edit it locally and subsequently commit and
push.

## Config generation

You can use the [Fab5 competitive config generation tool](https://fab5.team/tools/get5config/) to generate an adequate Get5 match config.
