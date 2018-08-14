FROM chekote/php:7.2.8

RUN apt-get update && \
    apt-get install --no-install-recommends --no-install-suggests -y \

        # project requirements
        php${PHP_VERSION}-mysql && \

    # Cleanup
    apt-get remove -y && \
    apt-get autoremove -y && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
