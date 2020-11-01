# system
Ansible role to configure basic system settings

## usage

| Variable     | Description                                                                                       | Example                           |
|--------------|---------------------------------------------------------------------------------------------------|-----------------------------------|
| system_users | Dictionairy of users and their passwords to be setup<br/>(Set password to '!' to disable the account) | - name: vseth<br/>&nbsp;&nbsp;password: 123456 |

**Important: For Linux, the password-value needs to be a hashed password. [Refer to this documentation](https://docs.ansible.com/ansible/latest/reference_appendices/faq.html#how-do-i-generate-encrypted-passwords-for-the-user-module)**
