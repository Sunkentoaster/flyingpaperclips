
## Setup
```
brew install hugo
git clone ...
git submodule update --init
```


to run the site locally, type `hugo server -D` within the flyingpaperclips directory


to do:

- the theme can be seen here: https://themes.gohugo.io/theme/strata/ -- the idea is to take the style from Recent Work and use that to display the posts




## Deployment

Deployed using Firebase Hosting.  We may need to do `firebase login`

```
hugo              # generates files in public folder
firebase deploy
```
