Notes
-----

Steps that were used to convert old moveable type blog, in original-website:  

```
npm install -g to-markdown-cli
mkdir posts
rm 200*/*/index.html
find 200* -type f -exec mv '{}' posts ';'
for file in *.html; do html2md -i "$file" -o "${file%.html}.md"; done
rm *.html
```