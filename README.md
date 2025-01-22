# Ansible

個人PCの初期環境設定で自動化できる部分を Ansible で設定する

## 環境構築

### Requirement

- Xcode
- [Homebrew](https://brew.sh/index_ja) がインストールされている
- [Ansible](https://formulae.brew.sh/formula/ansible) がインストールされている

### Install

```bash
user@host: ~ $ export PATH="/opt/homebrew/bin:$PATH"
user@host: ~/workspace/ansible $ ansible-playbook playbooks/mac/apple-m4.yaml
```
