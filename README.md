# korean
korean all document<br>

mkdir <repo><br>
cd <repo><br>
git init<br>
git remote add -f origin https://github.com/ithanks/korean.git<br>
git config core.sparseCheckout true<br>
echo "korean/dir/" >> .git/info/sparse-checkout<br>
echo "another/sub/tree" >> .git/info/sparse-checkout<br>
git pull origin master<br>
