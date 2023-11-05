FROM --platform=linux/amd64 jekyll/jekyll
#FROM jekyll/jekyll
LABEL maintainer="nikolai@zhivotenko.com"
# install imagemagick tool for convert command
RUN apk add --no-cache --virtual .build-deps \
        libxml2-dev \
        shadow \
        autoconf \
        g++ \
        make \
    && apk add --no-cache imagemagick-dev imagemagick
WORKDIR /srv/jekyll
ADD ../src/Gemfile /srv/jekyll/
# RUN bundle lock --add-platform ruby
# RUN bundle lock --add-platform x86_64-linux
RUN bundle install
