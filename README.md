# ansible-accumulo

An Ansible role for installing [Apache Accumulo](https://accumulo.apache.org/).

## Role Variables

- `accumulo_version` - Accumulo version.
- `accumulo_mirror` - A mirror for the Accumulo packages (default: `http://apache.mirrors.lucidnetworks.net`)
- `accumulo_conf_dir` - Configuration directory for Accumulo (default: `/etc/accumulo/conf`)
- `accumulo_log_dir` - Log directory for Accumulo (default: `/var/log/accumulo`)
- `accumulo_leader` - Flag to determine if a node is an Accumulo leader (default: False)

## Example Playbook

See the [examples](./examples/) directory.
