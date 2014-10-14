# ansible-sample
ansibleを利用して、haskell環境を作ってみる

## 構築方法
```
$ vagrant up
$ vagrant ssh-config >> ~/.ssh/config
$ ansible-playbook -i hosts haskell.yaml
```
