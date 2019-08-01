# ansible-role-mariadb

Ansible role for GitLab installation

### Prerequisites

** none **

## Deployment

Example playbook:

```
- hosts: gitlab
  roles:
    - 'ansible-role-gitlab'
```

Configure EXTERNAL_URL var in defaults/main.yml. This is the URL where your GitLab will accessed from. After that simply run your playbook:

```
ansible-playbook -i '<TARGET_HOST_IP>,' playbooks/mariadb.yml
```

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/2.8/index.html)

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## Company

* **Delta.BG**

## License

This project is licensed under the MIT License.
