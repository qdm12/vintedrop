# vintedrop

Drop periodically the price of all your items listed on your Vinted account

![Last release](https://img.shields.io/github/release/qdm12/vintedrop?label=Last%20release)
![Last Docker tag](https://img.shields.io/docker/v/qmcgaw/vintedrop?sort=semver&label=Last%20Docker%20tag)
![GitHub last release date](https://img.shields.io/github/release-date/qdm12/vintedrop?label=Last%20release%20date)
![Commits since release](https://img.shields.io/github/commits-since/qdm12/vintedrop/latest?sort=semver)

[![Latest size](https://img.shields.io/docker/image-size/qmcgaw/vintedrop/latest?label=Latest%20image)](https://hub.docker.com/r/qmcgaw/vintedrop/tags)
[![Last release size](https://img.shields.io/docker/image-size/qmcgaw/vintedrop?sort=semver&label=Last%20released%20image)](https://hub.docker.com/r/qmcgaw/vintedrop/tags?page=1&ordering=last_updated)

[![GitHub last commit](https://img.shields.io/github/last-commit/qdm12/vintedrop.svg)](https://github.com/qdm12/vintedrop/commits/main)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/y/qdm12/vintedrop.svg)](https://github.com/qdm12/vintedrop/graphs/contributors)
[![GitHub closed PRs](https://img.shields.io/github/issues-pr-closed/qdm12/vintedrop.svg)](https://github.com/qdm12/vintedrop/pulls?q=is%3Apr+is%3Aclosed)
[![GitHub issues](https://img.shields.io/github/issues/qdm12/vintedrop.svg)](https://github.com/qdm12/vintedrop/issues)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/qdm12/vintedrop.svg)](https://github.com/qdm12/vintedrop/issues?q=is%3Aissue+is%3Aclosed)

[![MIT](https://img.shields.io/github/license/qdm12/vintedrop)](https://github.com/qdm12/vintedrop/main/LICENSE)
![Code size](https://img.shields.io/github/languages/code-size/qdm12/vintedrop)
![GitHub repo size](https://img.shields.io/github/repo-size/qdm12/vintedrop)
![Go version](https://img.shields.io/github/go-mod/go-version/qdm12/vintedrop)
![Visitors count](https://visitor-badge.laobi.icu/badge?page_id=vintedrop.readme)
[![Build status](https://github.com/qdm12/vintedrop/actions/workflows/ci.yml/badge.svg)](https://github.com/qdm12/vintedrop/actions/workflows/ci.yml)

[![dockeri.co](https://dockeri.co/image/qmcgaw/vintedrop)](https://hub.docker.com/r/qmcgaw/vintedrop)

## Quick links

- Problem or suggestion?
  - [Start a discussion](https://github.com/qdm12/vintedrop/discussions)
  - [Create an issue](https://github.com/qdm12/vintedrop/issues)
- Happy?
  - Sponsor me on [github.com/sponsors/qdm12](https://github.com/sponsors/qdm12)
  - Donate to [paypal.me/qmcgaw](https://www.paypal.me/qmcgaw)
  - Drop me [an email](mailto:quentin.mcgaw@gmail.com)

## Features

- Pre-built standalone binary programs built for Linux, OSX and Windows
- Docker images available on [Docker Hub](https://hub.docker.com/r/qmcgaw/vintedrop) and [GitHub Container Registry](https://github.com/users/qmcgaw/packages/container/package/vintedrop)
- Docker images are multi-arch: `linux/amd64`, `linux/386`, `linux/arm64`, `linux/arm/v6`, `linux/arm/v7`.

## Usage

You can run the program either as a standalone binary or as a Docker container:

- Standalone binary
  1. Download the binary matching your platform from [the releases page](https://github.com/qdm12/vintedrop/releases).
  You can also install the binary from source using [Go](https://golang.org/dl/) with `go install github.com/qdm12/vintedrop/cmd/vintedrop`
  2. On Linux and OSX, make the binary executable with `chmod +x vintedrop`
  3. Run the binary with `./vintedrop`
- Docker container

  ```sh
  docker run --rm qmcgaw/vintedrop
  ```

  There also Docker tags matching each Github release, for example `:0.1.0` for release `v0.1.0`.
  The latest image tag matches the tip of the main branch.

### Options

| Flag | Environment variable | Default | Description |
|---|---|---|---|
| `--some-path` | `SOME_PATH` | `./path` | Path to some directory |
