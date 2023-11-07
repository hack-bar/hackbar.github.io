# hackbar.ch
This website requires the extended `hugo` binary. You can download that from [here](https://github.com/gohugoio/hugo/releases). 

## Dev/Live Server
Will open a live preview on [http://127.0.0.1:8081](127.0.0.1:8081)
`hugo server --noBuildLock --ignoreCache --disableFastRender -p 8081 --logLevel debug --minify -D -F`

## Prod Build
Will generate the folder `public`
`hugo --noBuildLock --logLevel debug --minify`

## New Event
+ Make a folder under `content/events`
+ Copy the template from `content/events/index.md.template` as `index.md` into the created folder
+ Modify the `index.md` to your liking. 
+ Rebuild the site

## Adding a gallery
Create a folder named `img` inside the event folder `content/events/YOUREVENT`. Hugo will then automatically add a gallery to the event and to the galleries page.

## :D
