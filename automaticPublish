#Need to do git add manually
read -p "Enter commit message : " commitMessage
#cd personalWeb
git commit -m "$commitMessage"
git push origin
bundle exec jekyll build
#bundle exec jekyll serve
rm -r ../ashantanu.github.io/*
cp -r _site/* ../ashantanu.github.io/ 
cd ../ashantanu.github.io
git add .
git commit -m "$commitMessage"
git push origin