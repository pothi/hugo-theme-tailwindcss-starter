# How to install for "themeless Hugo"

Ref: https://www.ii.com/themeless-gitless-intro-hugo/

```
git clone https://github.com/dirkolbrich/hugo-theme-tailwindcss-starter my-new-hugo-site
cd my-new-hugo-site
cp -a exampleSite/con* .
rm -rf exampleSite .git
git init

# following instructions are from the upstream repo
npm install -g postcss-cli autoprefixer
npm install
```

