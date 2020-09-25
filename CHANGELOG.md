<!--
SPDX-FileCopyrightText: 2020 Helmholtz Centre for Environmental Research (UFZ)
SPDX-FileCopyrightText: 2020 Helmholtz-Zentrum Dresden-Rossendorf (HZDR)

SPDX-License-Identifier: Apache-2.0
-->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Group your changes into these categories:

`Added`, `Changed`, `Deprecated`, `Removed`, `Fixed`, `Security`.

## Unreleased

[List of commits](https://gitlab.com/hifis/ansible/redis-role/-/compare/v0.1.0...master)

### Changed
- Upgrade Redis from version 6.0.6 to 6.0.8
([!19](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/19) 
by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).
- Improve and speed up the CI pipeline
  ([!20](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/20) 
  by [tobiashuste](https://gitlab.com/tobiashuste)).

## [0.1.0](https://gitlab.com/hifis/ansible/redis-role/-/releases/v0.1.0)

### Added
- Add initial molecule setup
([!1](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/1) 
by [Normo](https://gitlab.com/Normo)).
- Set up CI/CD.
([!3](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/3)
by [Normo](https://gitlab.com/Normo)).
- Make Redis Role idempotent
([!4](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/4)
by [Normo](https://gitlab.com/Normo) and [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).
- Add proper licensing to the project
([!5](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/5)
by [tobiashuste](https://gitlab.com/tobiashuste)).
- Provide templates for Systemd service files and make them configurable
([!11](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/11)
by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).
- Add file CHANGELOG.md and use Semantic Versioning
([!13](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/13)
by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).

### Changed
- Add defaults to Redis Ansible role and rename variables to more meaningful ones
([!2](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/2)
by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).
- Upgrade Redis from 6.0.5 to 6.0.6
([!6](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/6)
by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).
- Simplify version check
([!7](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/7)
by [Normo](https://gitlab.com/Normo)).
- Make the log level configurable
([!8](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/8)
by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).
- Make Redis protected-mode configurable and activate it
([!9](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/9)
by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).
- Only use one password variable instead of 3 equal ones
([!16](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/16)
by [tobiashuste](https://gitlab.com/tobiashuste))

### Fixed
- Redis / Sentinel service isn't restarted on update or config change
([!10](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/10)
by [christian.hueser.hzdr](https://gitlab.com/christian.hueser.hzdr)).
- Fix Redis Server and Sentinel not starting properly
([!15](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/15)
by [tobiashuste](https://gitlab.com/tobiashuste))
- Update project path to gitlab-ci templates
([!14](https://gitlab.com/hifis/ansible/redis-role/-/merge_requests/14)
by [Normo](https://gitlab.com/Normo))