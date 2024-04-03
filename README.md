# LIT 2024 Ansible testen mit Molecule

## 01-ansible-role

```bash
ansible-galaxy role init --offline setup-lit
```

change files

```bash
git add setup-lit
git commit -m "add ansible role setup-lit"
git push --set-upstream origin 01-ansible-role
```

## 02-molecule

```bash
molecule init scenario --help
Usage: molecule init scenario [OPTIONS] [SCENARIO_NAME]

molecule init scenario -d podman (default)
```

https://ansible.readthedocs.io/projects/molecule/examples/podman/
