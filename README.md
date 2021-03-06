# .github

organization level configuration repository

<!--status-badges start -->

[![Node CI Workflow Status][github-actions-ci-badge]][github-actions-ci-link]

<!--status-badges end -->

<!--consumer-badges start -->

[![MIT license][license-badge]][license-link]

<!--consumer-badges end -->

## Purpose

GitHub gives special behavior to a repository with the name of `.github`

* Defining community health files for use [as default files](https://help.github.com/en/articles/creating-a-default-community-health-file-for-your-organization#creating-a-repository-for-default-files)
  in repositories in the orgainzation that have not defined their own files
* Define default config for [Probot](https://probot.github.io) applications
  installed within the organization that use [`probot-config`](https://github.com/probot/probot-config)

## Contributing

<!--contribution-badges start -->

[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![PRs Welcome][PRs-badge]][PRs-link]
[![Dependabot][dependabot-badge]][dependabot-link]

<!--contribution-badges end -->

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

[commit-convention-link]: https://conventionalcommits.org

[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg

[commitizen-link]: http://commitizen.github.io/cz-cli/

[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg

[PRs-link]: http://makeapullrequest.com

[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg

[dependabot-link]: https://dependabot.com/

[dependabot-badge]: https://badgen.net/dependabot/dsmjs/.github/?icon=dependabot

[github-actions-ci-link]: https://github.com/dsmjs/.github/actions?query=workflow%3A%22Node.js+CI%22+branch%3Amaster

[github-actions-ci-badge]: https://github.com/dsmjs/.github/workflows/Node.js%20CI/badge.svg
