#######################################################
# APP_TARGET: full
#
# All of the dev/test/build tools
#######################################################
FROM ghcr.io/gostamp/ubuntu-full:0.3.1 AS full

# Drop down to the app user
USER app

# Copy app source
COPY . ${APP_DIR}
