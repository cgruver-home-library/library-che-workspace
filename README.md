# library-che-workspace
Eclipse Che Workspace Config

podman login quay.io/cgruver0

export BUILDAH_FORMAT=docker

podman buildx build --arch=amd64 -t quay.io/cgruver0/che/devtools:amd64 .
