# Logs
A simple lightweight webapp to create a blog/log.

## Problem statement
Even though there are numerous blogging platforms, I've been searching for something that is totally minimal and statically served without using any CMS software. Above of that the platform must be easy to use, especially adding or deleting new posts, even using mobile phones.

## How this webapp works
This application uses github Api to fetch paths of the current repo. The paths are used to get the list of the files available which are displayed as a list. New files can be created or existing files can be edited using github. Any change in repo files will change the displayed list.

## How to use this webapp
Create a new repo, simply clone this app, change the api URL to your username and newly created repo name. Push the changes and you are ready to use this.