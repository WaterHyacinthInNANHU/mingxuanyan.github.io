## About

My personal webpage ([link](https://WaterHyacinthInNANHU.github.io)). 

*Powered by [al-folio](https://github.com/alshedivat/al-folio). Thanks for the cool derivation by [cnut1648.github.io](https://github.com/cnut1648/cnut1648.github.io)*

## Install Dependencies
1. install python then `pip install jupyter`
2. install ruby 2.7.5 (run ridk install on the last stage of installation wizard which installs gem)
3. `gem install jekyll bundler`
4. When you are forking a template, remember that the repo name must be your github account name!

## For windows env
1. In `Gemfile` add `gem 'wdm', '>=0.1.0'` to the list if you are developing with windows.
2. Comment out the following
   ```
    external_sources: 
   - name: medium.com 
     rss_url: https://medium.com/@al-folio/feed 
   ```
   in `_config.yml`

## Config Url
1. open `_config.yml`
2. add your repo url behind `url:`
3. (optional) add a baseurl behind `url:`, for example, 'homepage'

## Edit Contents
1. go to `_pages` and change your information

## Bundle Init
1. (for windows) comment out `gem 'mini_racer'`
2. in the root folder, run `bundle install`

## Build and Preview Locally
1. in the root folder, run `bundle exec jekyll serve`
   1. if it shows permission denied in that port, just specify a port, for instance : `bundle exec jekyll serve --port 1234`
   2. if it shows something about the twitter/reddit connection errors, just clear the `_posts` folder and run again
2. An url will appear in the output where you can preview the page built.
3. Make changes to your pages and refresh the page then you can see the changes.

## Deployment
1. For the first deployment, follow the instructions [here](https://github.com/alshedivat/al-folio#deployment)
2. (for windows) uncomment `gem 'mini_racer'` as it is necessary for online deployment
3. Commit the changes and push to remote, github page will automatically build your site and update in one or two minutes. 

## References
1. [this cool video tutorial](https://www.youtube.com/watch?v=g6AJ9qPPoyc)
2. https://github.com/alshedivat/al-folio#installation