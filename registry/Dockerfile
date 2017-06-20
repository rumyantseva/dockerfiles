FROM registry:latest

ENV STORAGE_PATH /docker/registry
#ENV REGISTRY_STORAGE_FILESYSTEM_ROOTDIRECTORY /var/lib/registry
ENV REGISTRY_AUTH_HTPASSWD_REALM basic_realm
ENV REGISTRY_AUTH_HTPASSWD_PATH /auth/htpasswd
ENV REGISTRY_STORAGE_DELETE_ENABLED true

# Useful commands:
# /bin/registry garbage-collect --dry-run /etc/docker/registry/config.yml
