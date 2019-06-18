# How to install as "themeless Hugo"

Original Idea: https://www.ii.com/themeless-gitless-intro-hugo/

```
git clone https://github.com/dirkolbrich/hugo-theme-tailwindcss-starter my-new-hugo-site
# instead of the above line, the following should work too.
# git clone https://github.com/pothi/hugo-theme-tailwindcss-starter my-new-hugo-site

cd my-new-hugo-site
cp -a exampleSite/con* .
rm -rf exampleSite .git

# let's remove the line related to theme
sed -i '/^theme/d' config.toml

git init

# following instructions are from upstream repo
npm install -g postcss-cli autoprefixer
npm install
```

