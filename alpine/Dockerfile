FROM alpine:3.6

# Install build dependencies
RUN apk add --no-cache \
	--update-cache \
	autoconf \
	automake \
	bison \
	build-base \
	coreutils \
	curl \
	file \
	flex \
	gawk \
	git \
	gmp-dev \
	libtool \
	mpc1-dev \
	mpfr-dev \
	shadow \
	su-exec \
	texinfo \
	wget

# Add user and set entrypoint
RUN useradd -m -U -s /bin/sh -u 1234 user
