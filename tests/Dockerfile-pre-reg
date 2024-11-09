FROM registry.access.redhat.com/ubi8/ubi-minimal

# tests installing something that requires subscription repo
RUN microdnf -y install golang kernel-devel

# tests modules in general
RUN microdnf -y module enable nodejs:18 && \
    microdnf -y --nodocs install nodejs


FROM registry.access.redhat.com/ubi9/ubi-minimal

# tests installing something that requires subscription repo
RUN microdnf -y install golang kernel-devel

# tests modules in general
RUN microdnf -y module enable nodejs:18 && \
    microdnf -y --nodocs install nodejs



FROM registry.access.redhat.com/ubi8/ubi

# tests installing something that requires subscription repo
RUN dnf -y install golang kernel-devel

# tests modules in general
RUN dnf -y module enable nodejs:18 && \
    dnf -y --nodocs install nodejs

FROM registry.access.redhat.com/ubi9/ubi        

# tests installing something that requires subscription repo
RUN dnf -y install golang kernel-devel

# tests modules in general
RUN dnf -y module enable nodejs:18 && \
    dnf -y --nodocs install nodejs



