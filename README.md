### To start, copy the following commands:
```
export GITHUB_USERNAME=`gh api user | jq -r '.login'`
cd ~/code/${GITHUB_USERNAME}
gh repo clone git@github.com:AshIgnYeo/javascript-reboot.git
cd javascript-reboot
rm -rf .git
code .
```

### After that, to install the required packages, run
```
yarn install
```
