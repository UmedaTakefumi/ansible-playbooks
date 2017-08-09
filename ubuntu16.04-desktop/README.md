# ansible-playbooks

## Basic deb-package

```
ansible-playbook -i hosts, -c local roles/basic/tasks/main.yml
```

## virutalbox-5.1

```
ansible-playbook -i hosts, -c local roles/virutalbox/tasks/main.yml
```

## VSCode

```
 ansible-playbook -i hosts, -c local roles/vscode/tasks/main.yml
```

## linuxbrew

```
ansible-playbook -i hosts, -c local roles/linuxbrew/tasks/main.yml --extra-vars "user=ユーザー名"
```

## osquery

```
ansible-playbook -i hosts, -c local roles/osquery/tasks/main.yml
```

## docker-ce

```
ansible-playbook -i hosts, -c local roles/docker-ce/tasks/main.yml
```