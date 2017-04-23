# korean
korean all document

mkdir <repo>
cd <repo>
git init
git remote add -f origin <url>
git config core.sparseCheckout true
echo "korean/dir/" >> .git/info/sparse-checkout
echo "another/sub/tree" >> .git/info/sparse-checkout
git pull origin master
