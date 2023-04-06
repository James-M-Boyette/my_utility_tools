# Commands for initializing & pushing to a *new* GITHUB repo
        echo "# <WHATEVER_TITLE/TEXT_YOU_WANT_HERE>" >> README.md
        git init
        git add README.md
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/James-M-Boyette/<WHATEVER_YOUR_REPOs_NAME_IS.git
        git push -u origin main

# Commands for pushing an *existing* LOCAL repo *to* GITHUB
        git remote add origin https://github.com/James-M-Boyette/<WHATEVER_YOUR_REPOs_NAME_IS.git
        git branch -M main
        git push -u origin main