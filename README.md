# Ansible role for Jitsi Meet -- Secure, Simple and Scalable Video Conferences

This role installs [Jitsi Meet](https://github.com/jitsi/jitsi-meet).

## Example Playbook

The following is a minimal example playbook using this role.

```yml
- hosts: meet-server01
  become: true
  roles:
    - role: jitsi-meet
      jitsi_meet_hostname: meet.example.com
```

## Role variables

| Name                  | Default | Description                                     |
| :-------------------- | :------ | :---------------------------------------------- |
| `jitsi_meet_hostname` |         | Must be set to the publicly accessible hostname |
