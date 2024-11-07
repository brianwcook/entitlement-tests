FROM registry.access.redhat.com/ubi9/ubi-micro

# tests installing something that requires subscription repo
RUN microdnf -y install golang kernel-devel

# tests modules in general
RUN microdnf -y module enable nodejs:18 && \
    microdnf -y --nodocs install nodejs
