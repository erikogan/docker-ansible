# Changelog

## v4.2.3

- Upgrade Ansible to latest version 6.2.0
- Upgrade Ansible Lint to latest version 6.4.0
- Upgrade ansible-core 2.12 to latest version 2.12.8
- Upgrade ansible-core 2.13 to latest version 2.13.3

## v4.2.2

- Upgrade Ansible to v6.1.0 within 2.13
- Upgrade Ansible Core to latest version 2.13.2

## v4.2.1

- Resolve issues with ansible-lint pulling through Ansible 2.13 for 2.9 and 2.10. Resolves #52 in GitHub.

## v4.2.0

- Add ansible-core 2.13.1, ansible 6.0.0, ansible-lint 6.3.0
- Move latest to be Alpine 3.16, Ansible 2.13

## v4.1.1

- Resolves #43 - Loading mitogen 0.2.10 for < Ansible 2.10

## v4.1.0

- Add Ubuntu 22.04
- Add Alpine 3.16
- Resolve #47 - Incorrect Ansible version on 2.11 and 2.12 containers.
- Resolve #50 - non-matching version of Alpine.

## v4.0.2

- Add later Ansible versions:
  - 2.11.9, 2.11.10, 2.11.11
  - 2.12.3, 2.12.4, 2.12.5

## v4.0.1

- Add Debian Bullseye (+ Bullseye-Slim) for all Ansible versions.
- Create immutable images of all containers - need to work out some way of managing these longer term. Resolves #42.

## v4.0.0

- Restructure to make managing versions easier:
  - `ansible` (Ansible 2.9)
  - `ansible-base` (Ansible 2.10)
  - `ansible-core` (Ansible 2.11 + 2.12)
- Upgrade Ansible versions to latest.
- Alter to remove Centos 8 in favour of RockyLinux 8 - centos8 is EOL and Rocky Linux appears to be the most natural successor.
- Remove Alpine 3.11

## v3.2.0

- Alter `latest` to use ansible 2.11 and alpine 3.14.
- Remove Alpine 3.11 as past end of life
- Add Alpine 3.15 as new version
- Add Ansible version 2.12
- Upgrade ansible 2.11 to 2.11.7
- Upgrade ansible 2.10 to 2.10.16

## v3.1.2

- Update ansible 2.11 to version 2.11.6 and include `ansible` package. Resolves #40.
- Update ansible 2.10 to 2.10.15 - moving to `ansible-base` package.
- Update ansible 2.9 to version 2.9.27.
- Fix Alpine 3.14 builds. Resolves #41.

## v3.1.0

- Upgrade Ansible 2.9.23 to 2.9.24.
- Add Alpine 3.14 as OS.

## v3.0.0

- Add Ansible 2.11 for all OS. Resolves #35.

## v2.10.0

- Removes Ubuntu 16.04. Resolves #38.

## v2.9.0

- Remove Ansible 2.8. Resolves #37.

## v2.8.0

- Update Ansible versions where appropriate.
- Fix `pip` inside Ubuntu 16.04
- Fix Docker labels (resolves #36)

## v2.7.1

- Update Ansible versions where appropriate.
- Fix changelog.

## v2.7.0

- Correct tags within Docker Hub. Resolves #31
- Move to build within GitLab CI (and push to Docker Hub) due to limitations
- Correctly release Ansible v2.9
- Correctly add Centos-8. Resolves #32
- Fix #33 for build with Rust Cryptography.

## v2.6.0

- Bump Ansible Version to latest
- Add Alpine 2.13
- Add Centos-8

## v2.5.0

- Bump Ansible version to 2.8.15 and 2.9.13
- Add Dockerfile for build of Ansible 2.10 (2.10.1)
- Update README for better availability of Mitogen path
- Update GitLab CI for build inside GitLab

## 2.4

- Add `jmespath` for enabling json_filter inside json objects.
- Bump version of Ansible to latest stable (2.8.14 and 2.9.12)

## 2.3

- Add Ubuntu 20.04 version for Ansible 2.8 and 2.9
- Correct some tagging of releases
- Correct build of buster image for GitLab registry

## 2.2

- Update Ansible versions to 2.8.12 and 2.9.9

## 2.1

- Update documentation
- Ensure builds process in Docker Hub and GitLab

## 2.0

- Upgrade to Python 3 - Resolves #13
- Add Alpine 3.11
- Add Debian Buster
- Remove Alpine 3.9

## 1.2

- Upgrade Ansible 2.7 versions to 2.7.14. Resolves #12.

## 1.1

- Add Alpine v3.10 for later uses. Resolves #6.
- Add CHANGELOG.md. Resolves #5.
- Add git package for pulling roles from Ansible Galaxy. Resolves #4.
- Make /ansible directory and set as WORKDIR. Resolves #2.

## 1.0

- Initial release
