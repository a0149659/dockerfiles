FROM alpine:latest

RUN apk --no-cache add \
	libvirt-client

ENTRYPOINT [ "virsh", "-c", "qemu:///system" ]
