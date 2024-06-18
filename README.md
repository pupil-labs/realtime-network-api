[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/pupil-labs/realtime-network-api/main.svg)](https://results.pre-commit.ci/latest/github/pupil-labs/realtime-network-api/main)

# Pupil Labs Realtime Network API

The Pupil Labs Realtime Network API is used for streaming data from the Companion App in realtime over the local network.
It is also used to send realtime events and remotly control the Companion App.

This repository contains the [OpenAPI](https://swagger.io/specification/) specification
for the Pupil Labs Realtime Network API.


You can either browse it on
https://pupil-labs.github.io/realtime-network-api/ or see the raw formats here:

- [Pupil Labs Neon Companion Realtime API v2.1.0](https://raw.githubusercontent.com/pupil-labs/realtime-network-api/main/neon/v2.1.0.yaml).
- [Pupil Labs Neon Invisible Realtime API v1.1.0](https://raw.githubusercontent.com/pupil-labs/realtime-network-api/main/invisible/v1.1.0.yaml).

## Client Implementations

We have written a python client as a wrapper around the API that is very easy to use.
- [Realtime Python API](https://github.com/pupil-labs/realtime-python-api)
