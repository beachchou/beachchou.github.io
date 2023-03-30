---
---
1. install ruby ruby-dev g++ make

sudo apt-get install ruby ruby-all-dev

sudo apt install g++

sudo apt install make

2. 

export GEM_HOME=$HOME/gems
export PATH=$HOME/gems/bin:$PATH

add to ~/.bashrc

3.

gem install jekyll bundler

4. jekyll new myblog
5. cd myblog
6. bundle install
7. bundle exec jekyll serve