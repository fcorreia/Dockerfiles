FROM alpine:3.9




RUN apk update && apk add alpine-sdk && apk add libsrtp-dev=1.5.4-r1 \
    && apk add ncurses-dev \
    && curl -OL http://downloads.asterisk.org/pub/telephony/asterisk/releases/asterisk-18.3.0.tar.gz \
    && curl -OL http://downloads.asterisk.org/pub/telephony/asterisk/releases/asterisk-18.3.0.sha256 \
    && apk add autoconf automake gcc libgc++ libstdc++6 perl jansson-dev sqlite-dev=3.28.0-r3 libxml2-dev \
    libxslt-dev ncurses-dev openssl-dev openssl-dev newt-dev ncurses-dev libcap-dev gtk+2.0-dev \
    libsrtp-dev=1.5.4-r1 popt-dev gmime-dev doxygen graphviz libxml2-dev neon-dev libical-dev libxml2-dev \
    speex-dev=1.2.0-r0 speexdsp-dev libogg-dev libvorbis-dev gsm-dev  libedit-dev ilbc-dev libuuid libcurl \
    curl-dev dahdi-tools-dev=2.11.1-r0 libpri-dev spandsp-dev tiff-dev libjpeg-turbo-dev lua-dev libresample \
    portaudio-dev freetds-dev openldap-dev mariadb-dev mariadb-connector-c-dev libtool unixodbc-dev \
    postgresql-dev libpq freeradius-client-dev net-snmp-dev lm_sensors-dev imap-dev jansson-dev \
    freeradius-radclient alsa-lib-dev sdl-dev sdl_image-dev alsa-lib-dev bluez-dev bluez-libs

uuid-dev
latex2html
kernel-headers systemd
jack-audio-connection-kit-dev
SDL-devel SDL_image-devel  alsa-lib-devel bluez-libs-devel corosynclib-devel
 mISDN-dev

libss7-devel
>=
2.0.0