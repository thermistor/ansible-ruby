# Ansible role for ruby

This builds ruby on recent Ubuntu LTS or CentOS.

## Example playbook

Basic setup which installs the latest ruby (3.1.2) and latest bundler gem (2.3.20):

    - role: ruby

An example showing options you can set (NOTE: checksum is for xz file extension for versions > 3.0, and bz2 for lower versions).

    - role: ruby
      ruby_major_minor: 3.1
      ruby_version: 3.1.2
      ruby_version_checksum: sha256:ca10d017f8a1b6d247556622c841fc56b90c03b1803f87198da1e4fd3ec3bf2a
      ruby_bundler_version: 2.3.20

## License

MIT
