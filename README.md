


# Usage


```shell
  $ sudo apt-get update
  $ sudo apt-get install ssh
  $ sudo apt-get install ansible
```

```shell
  $ git clone https://github.com/archaicdust/cython_env_demo.git
  $ cd cython_env_demo

  $ ansible-playbook -K -i inventory playbook.yml

  # If you want to override the user name in the playbook.yml.
  $ ansible-playbook -u <use_name> -K -i inventory playbook.yml
```
