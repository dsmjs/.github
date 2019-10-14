# Contributing to dsmJS Projects

## Pull Requests

[![PRs Welcome][PRs-badge]][PRs-link]

We welcome and appreciate helpful contributions from the community. We do ask
that they are focused on the intended goal and unrelated changes are separated
into additional PRs.

### Align with maintainers first

We encourage conversation about your contribution ahead of opening your PR and
encourage aligning with project maintainers before investing significant effort
into your contribution.

Keep in mind that you are making a contribution to a project that is not your
own, so your first step is to convince the maintainers that your contribution
is one that they want to include in the project and maintain going forward.
Reaching concensus before you've made a significant investment in your
contribution will help the process go smoothly for everyone involved.

Opening an issue first is a great way to start the conversation about your
contribution idea. In addition, the maintainers can often be reached on the DSM
Web Collective Slack group. If you're not already a member, you can request an
invite at <http://dsmwebcollective.com>.

### Your first PR

If you are new to the process of making contributions through sending a
pull-request to a project, [this tutorial][PRs-link] can help get you started.

### Commit Convention

[![Conventional Commits][commit-convention-badge]][commit-convention-link]

We publish our pacakages automatically using
[semantic-release](https://github.com/semantic-release/semantic-release/).
Following a commit convention allows `semantic-release` to determine the impact
of each commit since the previous release and publish a [semver](https://semver.org)
compatible version with the new changes.

We have chosen to follow the [conventional commits][commit-convention-link]
convention. We leverage [commitlint](https://github.com/conventional-changelog/commitlint)
and a [`commitmsg` git hook](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
to automatically verify the commit syntax and remind to follow the convention
properly. You can find the versioning strategy for this convention [here](https://github.com/semantic-release/commit-analyzer#default-rules-matching).

While the commit convention is most useful in the package projects because of
the use of `semantic-release`, we do use the same convention on our other
projects for consistency.

#### Using a wizard to format commits correctly

[![Commitizen friendly][commitizen-badge]][commitizen-link]

In projects where you find the "commitizen friendly" badge, we have configured
the cli wizard called [commitizen][commitizen-link] in order to simplify
building the commit message correctly. If you are new to `commitizen`, simply
[install the tool](https://commitizen.github.io/cz-cli/#installing-the-command-line-tool)
and then use `git cz` to commit instead of the usual `git commit`.

:eyes: __Note__: If your commit fails and you have adjusted the staged files
and want to attempt your commit again, you can use the `git cz --retry` command
to use the previous wizard answers rather than answering the same way a second
time.

## Environment Configuration

### Node / npm

We define an expected node in each project using [nvm](https://github.com/nvm-sh/nvm)
to help enable consistency between contributors as well as CI.

Once you have `nvm` installed, you can use `nvm install` after cloning to
configure your local node version to match what is expected for the project
(`nvm use` will also work for versions that you already have installed). Avoid
upgrading `npm` independently so that the installed version remains the one
installed with the node version. This will help reduce noise between commits
within the `package-lock.json` file.

If you use `nvm` in many projects, you might consider using [avn](https://github.com/wbyoung/avn)
and [avn-nvm](https://github.com/wbyoung/avn-nvm) to automatically switch to
configured versions when changing into a directory.


[commit-convention-link]: https://conventionalcommits.org
[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg
[commitizen-link]: http://commitizen.github.io/cz-cli/
[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[PRs-link]: http://makeapullrequest.com
[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg

