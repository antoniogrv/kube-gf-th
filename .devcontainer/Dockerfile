FROM qmcgaw/latexdevcontainer:latest-full

# The following is required in order for the 'minted' TeX package to work properly.

RUN apt update && \
    apt install \
        python \
        python3-pip \
    -y --no-install-recommends

RUN pip install Pygments