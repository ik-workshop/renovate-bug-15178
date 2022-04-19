# Renovate Bug Fix

Labels not set when there is an empty label. The renovate congiration does not validate user input, or runtime label setup.
Github API does not let to push empty labels. Renovate can have a behaviour changed slightly.

- [Issue](https://github.com/renovatebot/renovate/issues/15178)
- [Bug fix. TODO]()

- [Pre-commit support](https://docs.renovatebot.com/modules/manager/pre-commit/)
- [commitMessageSuffix](https://docs.renovatebot.com/configuration-options/#commitmessagesuffix)

---

![](https://img.shields.io/github/commit-activity/m/ik-workshop/renovate-bug-15178)
![](https://img.shields.io/github/last-commit/ik-workshop/renovate-bug-15178)
[![](https://img.shields.io/github/license/ivankatliarchuk/.github)](https://github.com/ivankatliarchuk/.github/LICENCE)
[![](https://img.shields.io/github/languages/code-size/ik-workshop/renovate-bug-15178)](https://github.com/ik-workshop/renovate-bug-15178)
[![](https://img.shields.io/github/repo-size/ik-workshop/renovate-bug-15178)](https://github.com/ik-workshop/renovate-bug-15178)
![](https://img.shields.io/github/languages/top/ik-workshop/renovate-bug-15178?color=green&logo=markdown&logoColor=blue)

---

[![governance][governance-badge]][governance-action]
[![governance.link-checker][governance.link-checker.badge]][governance.link-checker.status]

---

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Contents

- [Example](#example)
  - [Example 1](#example-1)


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

---

## Example

### Example 1

DepType not available. It can be mitiged with more complex configuration.

> depType: The dependency type (if extracted - manager-dependent)

```sh
make example1
```

- [Renovate config](./config-ex1.js)


## How to run

## Create

[**Create a repository using this template →**][template.generate]

## Resources

- [Renovate: documentation](https://docs.renovatebot.com/)
- [Renovate: docs template fields](https://docs.renovatebot.com/templates/)

<!-- resources -->
[template.generate]: https://github.com/ik-workshop/renovate-bug-15178/generate
[code-style.badge]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square

[governance-badge]: https://github.com/ik-workshop/renovate-bug-15178/actions/workflows/governance.bot.yml/badge.svg
[governance-action]: https://github.com/ik-workshop/renovate-bug-15178/actions/workflows/governance.bot.yml

[governance.link-checker.badge]: https://github.com/ik-workshop/renovate-bug-15178/actions/workflows/governance.links-checker.yml/badge.svg
[governance.link-checker.status]: https://github.com/ik-workshop/renovate-bug-15178/actions/workflows/governance.links-checker.yml
