# Git sparsecheckout

- git init
- git remote add -f origin https://github.com/eugenp/tutorials.git
- git checkout -b master
- git config core.sparsecheckout true
- git sparse-checkout init
- git sparse-checkout set /spring-boot-modules/spring-boot-react/
- git pull origin master
