# maven-no-root
Docker Image based on official maven image but adding non root user 'maven' as default user.

Useful for some Gitlab-ci scripts where java Integration tests require to create folders in tmp.
