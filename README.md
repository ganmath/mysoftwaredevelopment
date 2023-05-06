# Git sparsecheckout

- git init
- git remote add -f origin https://github.com/eugenp/tutorials.git
- git checkout -b master
- git config core.sparsecheckout true
- git sparse-checkout init
- git sparse-checkout set /spring-boot-modules/spring-boot-react/
- git pull origin master

## references :
1. https://linuxhint.com/what-is-git-sparse-checkout/
2. https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists
