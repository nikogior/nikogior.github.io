# nikogior.github.io

# Working on the website using Jekyll
## Installing Jekyll:

Follow the steps from here to install the Jekyll prerquisites on MacOs:
- https://jekyllrb.com/docs/installation/macos/

Then continue with the following: 
- https://jekyllrb.com/docs/

## Creating a new site:

Follow the steps from:
- https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll 
```sh
# Install jekyll and bundler ruby gems
gem install jekyll bundler
bundle add webrick

# Create a new Jekyll site at "./devops-portfolio"
jekyll new devops-portfolio

# Build the site and make it available
cd devops-portfolio
bundle exec jekyll serve
```