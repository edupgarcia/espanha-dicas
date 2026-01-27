FROM jekyll/jekyll:4.2.2

WORKDIR /srv/jekyll

# Install Ruby gems
COPY Gemfile Gemfile.lock ./
RUN bundle install
