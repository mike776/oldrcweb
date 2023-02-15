# rainbowcrow.com
Rainbow Crow LLC website

*Everything should be done in the `site` directory*

# How to pull the latest changes from git
`git pull`.

# To view the site offline (with live changes)
`hugo -D serve`

# How to update git
```sh
# Check the current changed files
git status

# Check the line by line changes
git diff

# Add the files to the 'staging area'
git add -A

# Package the changes into a 'commit'
git commit -m "change summary"

# Push the commit to github
git push
```

# To build the site before uploading
`hugo`

# To upload the site
scp -r public/* rainbowcrow:/var/www/rainbowcrow.com/web/

*Most modifications happen in `site/data` directory*
