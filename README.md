# Workflows Course

This project is an example of workflow management for a lynda.com course.

# Setup in Ubuntu 14.04
```
# Install global dependencies
sudo apt-get update -y
sudo apt-get install ruby ruby-dev nodejs npm -y
sudo gem install sass
sudo gem install compass
sudo npm install -g gulp
sudo npm install -g browserify
# Install all local dependencies (see package.json)
npm install
# Run app with gulp automation at localhost:8080
gulp
```
