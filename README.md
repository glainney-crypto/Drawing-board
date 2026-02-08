# Drawing-board
Cute drawing board for Notion
cd /path/to/Drawing-board
git init
git add .
git commit -m "Prepare site: add index.html, Pages workflow, README"
git branch -M main
git remote add origin https://github.com/glainney-crypto/Drawing-board.git


gh api /repos/glainney-crypto/Drawing-board/pages --jq .html_url
# or open https://glainney-crypto.github.io/Drawing-board
