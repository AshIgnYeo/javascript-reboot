### To start, copy the following commands:
```
export GITHUB_USERNAME=`gh api user | jq -r '.login'`
mkdir -p ~/code/${GITHUB_USERNAME}/reboots && cd $_
gh repo clone git@github.com:AshIgnYeo/javascript-reboot.git
cd javascript-reboot
rm -rf .git
yarn install
code .
```
Good luck! 🚀
