# kubernetes-vagrant
Kubernetes 를 실습할 수 있는 Vagrant 환경 구성

1. virtual box, vagrant, ansible, sshpass 설치

- [Virtual Box and vagrant](http://sourabhbajaj.com/mac-setup/Vagrant/README.html)
- [Ansible](https://hvops.com/articles/ansible-mac-osx/)
- [sshpass](https://gist.github.com/arunoda/7790979)

2. git clone

```bash
git clone https://github.com/powerumc/kubernetes-vagrant
cd kubernetes-vagrant
```

3. `vagrant up`

4. `cd ansible`

5. `ansible-playbook -i hosts playbook.yml`
