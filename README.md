# Community Hass.io Add-ons: Base Images

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

[![GitLab CI][gitlabci-shield]][gitlabci]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

[![Bountysource][bountysource-shield]][bountysource]
[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

[![Support my work on Patreon][patreon-shield]][patreon]

Docker base images used by Community Hass.io Add-ons.

## About

These are the base images used by add-ons created by the Community Hass.io
Add-ons.

While Home Assistant provides base images, the images provided by this
repository contain some extras:

- Adds [s6] as a process supervisor.
- Adds `jq` & `curl`, since every add-on uses them.
- Adds Docker [Label Schema][label-schema] support.
- Adds a large Bash function library for use with an add-on.
- Handles logs, add-on startup banners and update notifications.
- Several small adjustments and improvements.

## Docker status

[![Docker Architecture][armhf-arch-shield]][armhf-dockerhub]
[![Docker Version][armhf-version-shield]][armhf-microbadger]
[![Docker Layers][armhf-layers-shield]][armhf-microbadger]
[![Docker Pulls][armhf-pulls-shield]][armhf-dockerhub]
[![Anchore Image Overview][armhf-anchore-shield]][armhf-anchore]

[![Docker Architecture][aarch64-arch-shield]][aarch64-dockerhub]
[![Docker Version][aarch64-version-shield]][aarch64-microbadger]
[![Docker Layers][aarch64-layers-shield]][aarch64-microbadger]
[![Docker Pulls][aarch64-pulls-shield]][aarch64-dockerhub]
[![Anchore Image Overview][aarch64-anchore-shield]][aarch64-anchore]

[![Docker Architecture][amd64-arch-shield]][amd64-dockerhub]
[![Docker Version][amd64-version-shield]][amd64-microbadger]
[![Docker Layers][amd64-layers-shield]][amd64-microbadger]
[![Docker Pulls][amd64-pulls-shield]][amd64-dockerhub]
[![Anchore Image Overview][amd64-anchore-shield]][amd64-anchore]

[![Docker Architecture][i386-arch-shield]][i386-dockerhub]
[![Docker Version][i386-version-shield]][i386-microbadger]
[![Docker Layers][i386-layers-shield]][i386-microbadger]
[![Docker Pulls][i386-pulls-shield]][i386-dockerhub]
[![Anchore Image Overview][i386-anchore-shield]][i386-anchore]

## Changelog & Releases

This repository keeps a change log using [GitHub's releases][releases]
functionality. The format of the log is based on
[Keep a Changelog][keepchangelog].

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You have several options to get them answered:

- The [Community Hass.io Add-ons Discord chat server][discord] for add-on
  support and feature requests.
- The [Home Assistant Discord Chat Server][discord-ha] for general Home
  Assistant discussions and questions.
- The Home Assistant [Community Forum][forum].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also [open an issue here][issue] GitHub.

## Contributing

This is an active open-source project. We are always open to people who want to
use the code or contribute to it.

We've set up a separate document for our
[contribution guidelines](CONTRIBUTING.md).

Thank you for being involved! :heart_eyes:

## Authors & contributors

The original setup of this repository is by [Franck Nijhof][frenck].

For a full list of all authors and contributors,
check [the contributor's page][contributors].

## We have got some Hass.io add-ons for you

Want some more functionality to your Hass.io Home Assistant instance?

We have created multiple add-ons for Hass.io. For a full list, check out
our [GitHub Repository][repository].

## License

MIT License

Copyright (c) 2017 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[aarch64-anchore-shield]: https://anchore.io/service/badges/image/cb97eb5c6d6112657e409a9c467e0207ccd3104b59ead4ff3e0c756a0aee1d47
[aarch64-anchore]: https://anchore.io/image/dockerhub/hassioaddons%2Fbase-aarch64%3Alatest
[aarch64-arch-shield]: https://img.shields.io/badge/architecture-aarch64-blue.svg
[aarch64-dockerhub]: https://hub.docker.com/r/hassioaddons/base-aarch64
[aarch64-layers-shield]: https://images.microbadger.com/badges/image/hassioaddons/base-aarch64.svg
[aarch64-microbadger]: https://microbadger.com/images/hassioaddons/base-aarch64
[aarch64-pulls-shield]: https://img.shields.io/docker/pulls/hassioaddons/base-aarch64.svg
[aarch64-version-shield]: https://images.microbadger.com/badges/version/hassioaddons/base-aarch64.svg
[amd64-anchore-shield]: https://anchore.io/service/badges/image/5f06917b27fd112a2b3539dcd7cb542ae50fa5967f2cfa254d8adc8ffeaea2a3
[amd64-anchore]: https://anchore.io/image/dockerhub/hassioaddons%2Fbase-amd64%3Alatest
[amd64-arch-shield]: https://img.shields.io/badge/architecture-amd64-blue.svg
[amd64-dockerhub]: https://hub.docker.com/r/hassioaddons/base-amd64
[amd64-layers-shield]: https://images.microbadger.com/badges/image/hassioaddons/base-amd64.svg
[amd64-microbadger]: https://microbadger.com/images/hassioaddons/base-amd64
[amd64-pulls-shield]: https://img.shields.io/docker/pulls/hassioaddons/base-amd64.svg
[amd64-version-shield]: https://images.microbadger.com/badges/version/hassioaddons/base-amd64.svg
[armhf-anchore-shield]: https://anchore.io/service/badges/image/3723e45cd4af53cd941481ebdd84367f24775b5df040bee378f7cbfba0b8b171
[armhf-anchore]: https://anchore.io/image/dockerhub/hassioaddons%2Fbase-armhf%3Alatest
[armhf-arch-shield]: https://img.shields.io/badge/architecture-armhf-blue.svg
[armhf-dockerhub]: https://hub.docker.com/r/hassioaddons/base-armhf
[armhf-layers-shield]: https://images.microbadger.com/badges/image/hassioaddons/base-armhf.svg
[armhf-microbadger]: https://microbadger.com/images/hassioaddons/base-armhf
[armhf-pulls-shield]: https://img.shields.io/docker/pulls/hassioaddons/base-armhf.svg
[armhf-version-shield]: https://images.microbadger.com/badges/version/hassioaddons/base-armhf.svg
[bountysource-shield]: https://img.shields.io/bountysource/team/hassio-addons/activity.svg
[bountysource]: https://www.bountysource.com/teams/hassio-addons/issues
[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/guidelines/download-assets-sm-2.svg
[buymeacoffee]: https://www.buymeacoffee.com/frenck
[commits-shield]: https://img.shields.io/github/commit-activity/y/hassio-addons/addon-base.svg
[commits]: https://github.com/hassio-addons/addon-base/commits/master
[contributors]: https://github.com/hassio-addons/addon-base/graphs/contributors
[discord-ha]: https://discord.gg/c5DvZ4e
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[discord]: https://discord.me/hassioaddons
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io/?u=frenck
[frenck]: https://github.com/frenck
[gitlabci-shield]: https://gitlab.com/hassio-addons/addon-base/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/hassio-addons/addon-base/pipelines
[i386-anchore-shield]: https://anchore.io/service/badges/image/e84714210ab906e08ccc79c951cd8823996c8003dabcc86e18effb9f6d47ed0a
[i386-anchore]: https://anchore.io/image/dockerhub/hassioaddons%2Fbase-i386%3Alatest
[i386-arch-shield]: https://img.shields.io/badge/architecture-i386-blue.svg
[i386-dockerhub]: https://hub.docker.com/r/hassioaddons/base-i386
[i386-layers-shield]: https://images.microbadger.com/badges/image/hassioaddons/base-i386.svg
[i386-microbadger]: https://microbadger.com/images/hassioaddons/base-i386
[i386-pulls-shield]: https://img.shields.io/docker/pulls/hassioaddons/base-i386.svg
[i386-version-shield]: https://images.microbadger.com/badges/version/hassioaddons/base-i386.svg
[issue]: https://github.com/hassio-addons/addon-base/issues
[keepchangelog]: http://keepachangelog.com/en/1.0.0/
[label-schema]: http://label-schema.org/
[license-shield]: https://img.shields.io/github/license/hassio-addons/addon-base.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2018.svg
[patreon-shield]: https://www.frenck.nl/images/patreon.png
[patreon]: https://www.patreon.com/frenck
[project-stage-shield]: https://img.shields.io/badge/Project%20Stage-Production%20Ready-brightgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[releases-shield]: https://img.shields.io/github/release/hassio-addons/addon-base.svg
[releases]: https://github.com/hassio-addons/addon-base/releases
[repository]: https://github.com/hassio-addons/repository
[s6]: http://skarnet.org/software/s6/overview.html
[semver]: http://semver.org/spec/v2.0.0.html
