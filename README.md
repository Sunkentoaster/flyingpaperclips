to run the site locally, type `hugo server -D` within the flyingpaperclips directory


to do:

- add content from old site
- the theme can be seen here: https://themes.gohugo.io/theme/strata/ -- the idea is to take the style from Recent Work and use that to display the posts



Notes
-----

Steps that were used to convert old moveable type blog, in original-website:  

```
npm install -g to-markdown-cli
mkdir posts
rm 200*/*/index.html
find 200* -type f -exec mv '{}' posts ';'
```