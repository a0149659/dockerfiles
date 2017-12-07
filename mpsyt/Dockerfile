FROM python:3-alpine

RUN apk add --no-cache \
	mplayer \
	mpv

RUN pip install mps-youtube

ENTRYPOINT ["mpsyt"]
