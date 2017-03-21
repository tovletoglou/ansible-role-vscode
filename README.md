# Ansible Role: Visual Studio Code

Install [Visual Studio Code](https://code.visualstudio.com/) from Microsoft repository.

## Requirements

- Ansible >= 2.2
- Fedora 25
- sudo

The role may run on other systems, but it is not tested.

## Role Variables

Keep VSCode update (present | latest | absent).

```
vscode_update: latest
```

## Example

```
- hosts: all
  roles:
    - ansible-role-vscode
```

## Dependencies

None

## License

MIT

## Author Information

Apostolos Tovletoglou [ansible-role-vscode](https://github.com/tovletoglou/ansible-vscode)
