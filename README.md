# ansible-test-web-server
テスト用のWEBサーバ構築のための playbook

## 必要ロール
* [geerlingguy.certbot](https://galaxy.ansible.com/geerlingguy/certbot)
* [histudy/ansible-role-apt-backports](https://github.com/histudy/ansible-role-apt-backports)
* [histudy/ansible-role-nginx](https://github.com/histudy/ansible-role-nginx)  
* [histudy/ansible-role-common](https://github.com/histudy/ansible-role-common)
  * Debian Bullseye が対象の場合は、[for-bullseye](https://github.com/histudy/ansible-role-common/tree/for-bullseye)ブランチを使用する
