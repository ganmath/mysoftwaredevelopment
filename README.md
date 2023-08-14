# Git sparsecheckout

- git init
- git remote add -f origin https://github.com/eugenp/tutorials.git
- git checkout -b master
- git config core.sparsecheckout true
- git sparse-checkout init
- git sparse-checkout set /spring-boot-modules/spring-boot-react/
- git pull origin master
# Git sparsecheckout
- git clone <URL> --no-checkout <directory>
- cd <directory>
- git sparse-checkout init --cone # to fetch only root files
- git sparse-checkout set apps/my_app libs/my_lib # etc, to list sub-folders to checkout
- git checkout # or git switch

## references :
1. https://linuxhint.com/what-is-git-sparse-checkout/
2. https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists
