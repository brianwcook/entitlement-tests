FROM registry.access.redhat.com/ubi9/ubi

RUN subscription-manager --enablerepo codeready-builder-for-rhel-9-x86_64-rpms && \
    --enablerepo jws-5-for-rhel-9-x86_64-rpms && \
     dnf -y install golang kernel-devel java-17-openjdk-headless && \ 
     dnf -y  groupinstall jws5
