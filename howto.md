## Install Dependencies
1. install python
2. `pip install jupyter`
3. ruby
4. 

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
3. (optional) add a baseurl behind `url:`, for example, 'aboutme'

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


