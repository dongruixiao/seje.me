SEJE.ME

```
# clone repo

git clone git@github.com:dongruixiao/seje.me.git
git submodule update --init

# write post

hugo new post/new-post.md
vim content/post/new-post.md

# submit

rm -rf docs && hugo
git add .
git commit -m 'new post'
git push

```
