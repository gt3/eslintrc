# eslintrc



* Following command will add this repo as submodule: 

  `git submodule add https://github.com/gt3/eslintrc config/eslint`
  
* Specify config file to eslint:

  `eslint -c ./config/eslint/.eslintrc.json src/**`

* To incldue submodules during clone use:

  `git clone --recursive <project url>`
  
* To add submodules to already cloned repo:

  `git submodule update --init`
  
* To update submodule from remote:

  `git submodule update --remote`


Note: Eslint rules used in _.eslintrc.json_ may seem too forgiving. Perhaps another _.eslintrc-strict_ needs to be added?
