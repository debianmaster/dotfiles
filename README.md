# dotfiles
```
alias apb='docker run --rm --privileged -v $PWD:/mnt -v /var/run/docker.sock:/var/run/docker.sock -v $HOME/.kube:/.kube -e DOCKER_TLS_VERIFY="1" -u $UID docker.io/ansibleplaybookbundle/apb-tools  "$@"'
```
