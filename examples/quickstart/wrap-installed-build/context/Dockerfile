# Extend the base image containing the patched version of Wine
ARG UE_VERSION='invalid'
FROM soncresityindustries/autosdk-wine:${UE_VERSION}

# Copy the Installed Build of Nythera Engine to C:\nye under our Wine prefix
COPY --chown=nonroot:nonroot ./nye ${WINEPREFIX}/drive_c/nye
