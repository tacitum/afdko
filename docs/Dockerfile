FROM ruby:2.7
RUN gem install jekyll bundler
WORKDIR /src
ENV PAGES_REPO_NWO=adobe-type-tools/afdko
ENV LC_ALL C.UTF-8
ENV LANG en_US.UTF-8
ENV LANGUAGE en_US.UTF-8
ENTRYPOINT bundle update && bundle exec jekyll serve \
  --host 0.0.0.0 
