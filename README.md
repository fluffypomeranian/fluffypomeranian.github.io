# Timothy Siwula

This [repository](https://github.com/fluffypomeranian/timsiwula.github.io
)
is for my [portfolio](https://www.timsiwula.com) and future blog and future mailing list.


## install then start docker server
Build the site with the following command

```
# cd /Users/tim.siwula/dev/fluffypomeranian.github.io

# start docker desktop
// chmod 777 build.sh
./build.sh server
open http://0.0.0.0:4000/

```

# debug
gem install bundler
gem update --system
bundle install
bundle update
\curl -sSL https://get.rvm.io | bash -s stable
source /Users/tim.siwula/.rvm/scripts/rvm
rvm install 2.6.5
brew install cocoapods --build-from-source
