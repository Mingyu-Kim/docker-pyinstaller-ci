# docker-pyinstaller-ci
PyInstaller for Windows inside Docker (using Wine). Usable for GitLab CI.

This is a very simple image built on top of the amazing [engineervix/pyinstaller-windows](https://hub.docker.com/r/engineervix/pyinstaller-windows) ([source](https://github.com/engineervix/docker-pyinstaller)). It only removes the entrypoint script, making it possible (and very easy) to use this image in [GitLab CI](https://about.gitlab.com/gitlab-ci/).
