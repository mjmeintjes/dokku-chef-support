FROM progrium:buildstep
MAINTAINER mattsum "matthys@mattsum.com"

RUN apt-get -y update
RUN apt-get -y install curl
RUN curl -L https://www.opscode.com/chef/install.sh | bash
RUN echo "gem: --no-ri --no-rdoc" > ~/.gemrc
RUN /opt/chef/embedded/bin/gem install berkshelf
