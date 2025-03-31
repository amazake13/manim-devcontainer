FROM manimcommunity/manim

USER root

RUN apt-get update && apt-get install -y --no-install-recommends \
    xdg-utils \
    vlc \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

USER manimuser
