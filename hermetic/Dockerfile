FROM registry.access.redhat.com/ubi9/ubi

RUN subscription-manager --enablerepo codeready-builder-for-rhel-9-x86_64-rpms && \
     dnf -y install golang kernel-devel
