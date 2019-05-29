# .github

organization level configuration repository

<!-- status badges -->
[![Build Status][ci-badge]][ci-link]

<!-- consumer badges -->
[![MIT license][license-badge]][license-link]

## Purpose

GitHub gives special behavior to a repository with the name of `.github`

* Defining community health files for use [as default files](https://help.github.com/en/articles/creating-a-default-community-health-file-for-your-organization#creating-a-repository-for-default-files)
  in repositories in the orgainzation that have not defined their own files
* Define default config for [Probot](https://probot.github.io) applications
  installed within the organization that use [`probot-config`](https://github.com/probot/probot-config)

## Contributing

<!-- contribution badges -->
[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![PRs Welcome][PRs-badge]][PRs-link]

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[license-link]: LICENSE
[license-badge]: https://img.shields.io/github/license/dsmjs/.github.svg
[ci-link]: https://travis-ci.com/dsmjs/.github
[ci-badge]: https://img.shields.io/travis/com/dsmjs/.github/master.svg
[commit-convention-link]: https://conventionalcommits.org
[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg
[commitizen-link]: http://commitizen.github.io/cz-cli/
[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[PRs-link]: http://makeapullrequest.com
[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
