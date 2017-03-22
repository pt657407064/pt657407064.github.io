# gh-pages-workshop
Sample HTML template to clone for the workshop

## How to use:
Create repository on your Github account with name {your-user-name}.github.io (i.e. theAlexPatin.github.io)

Open Git Bash on Windows, Terminal on Mac/Ubuntu:
```
git clone https://github.com/theAlexPatin/gh-pages-workshop.git website
cd website
rm -rf .git
git init
git remote add origin https://github.com/{your-user-name}/{your-user-name}.github.io.git
git add --all
git commit -m "Some Message"
git push origin master
```    

Then link your gh-pages to your domain with this [https://www.namecheap.com/support/knowledgebase/article.aspx/9645/2208/how-do-i-link-my-domain-to-github-pages](tutorial)
