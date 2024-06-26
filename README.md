# go_to_sleep
Simple webpage with advice on getting better sleep. 
Straightforward CSS, simple JS functions like dark mode button or popup that shows up after 30 seconds. Kind of responsive. 

No templates used -- each .html file needs to be edited separately

## How to deploy a site - GitHub (Recommended)
1. Register at github.com - pick a username you wouldn't mind being public
2. Fork a repository: https://github.com/inthecure/go_to_sleep - [How to fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
3. Rename your repository to _username_.github.io - [How to rename](https://docs.github.com/en/repositories/creating-and-managing-repositories/renaming-a-repository)
4. Go to _username_.github.io - this is your copy of a go_to_sleep website

_works for static sites only_

## How to deploy a site - Render (Customizeable)

1. Register at github.com
2. Register at render.com -- choose free price plan
3. Fork a repository: https://github.com/inthecure/go_to_sleep
4. Go to Render dashboard:  https://dashboard.render.com/
5. Click New > Static Site > Connect Repository
6. Enter your site name -- it will look like example.render.com
7. Enter a dot . under Publish Directory -- leave other settings unchanged
8. Click Create Static Site

_works for all sites_

## What next

- Go to github.com > click profile picture in top right > Your Repositories
- Click on the name of your repository -- go_to_sleep /
- Click on index.html > click edit file in top right
- Paste Pixel code between <head> and </head> tags
- Commit changes
- Experiment:
  *  install events
  *  set up custom conversions
  *  use Event Setup Tool
  *   verify domain

[How to edit](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files)

## Setup tips

Site pages are files ending with .html - index.html is the home page

Each .html page is separate from other -- so a Pixel needs to be set up on every page separately. 

Same goes for any code: events, domain verification, etc.

## Resources

How to set up and install a Meta Pixel: https://www.facebook.com/business/help/952192354843755

Use the Facebook event setup tool for web:
https://www.facebook.com/business/help/777099232674791

Use custom conversions to log standard events without code: https://www.facebook.com/business/help/723326514751348

Specifications for Meta Pixel standard events:
https://www.facebook.com/business/help/402791146561655 

Conversion tracking: 
https://developers.facebook.com/docs/meta-pixel/implementation/conversion-tracking/
