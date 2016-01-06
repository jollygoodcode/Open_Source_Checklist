# Open Source Checklist

[Copy-paste friendly version](/COPYME.md).

## General

- [ ] README file
  * Keep README short
  * Badges from CI, Code Coverage, Code Climate etc
    - https://github.com/badges/badgerbadgerbadger
    - http://shields.io/
  * Why? What is this project? What problem it solved?
  * Known issues if any
  * Features
  * Usage / Synopsis
  * Roadmap / Todos
  * How to Contact (IRC, Gitter, Slack, Mailing List)
  * Link to CONTRIBUTING.md
  * Link to LICENSE
  * Link to DEPLOYMENT.md
  * Credits
- [ ] CHANGELOG file
  * http://keepachangelog.com
  * Follow SemVer 2.0 http://semver.org
- [ ] LICENSE file
  * http://choosealicense.com
  * Year
  * Author(s) Name
- [ ] CONTRIBUTING file
  * General Guidelines
  * How to Set Up Development Environment?
  * How to Run Test Suite?
  * How to Run Extra Scripts (Linters)?
  * How to Release?
  * Contributor License Agreement (CLA)
  * [This file is special on GitHub](https://github.com/blog/1184-contributing-guidelines)
- [ ] DEPLOYMENT file (Optional)
  * How to Deploy?
- [ ] Code of Conduct
  * http://contributor-covenant.org/version/1/3/0/code_of_conduct.md
- [ ] Tests
  * All passed!
- [ ] Wiki (Optional)
- [ ] CI Service
  * Setup CI service: Travis CI or Circle CI

All files are in markdown format (`.md`).

## RubyGem Specific

- Remove tests/specs from packaged gem [Why?](https://github.com/bundler/bundler/pull/3207)

## Rails Specific

- Remove sensitive data
- Remove unnecessary code
