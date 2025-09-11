# Ansible role for ruby

This builds ruby on recent Ubuntu LTS (CentOS needs testing).

## Example playbook

Basic setup which installs the latest ruby (3.4.5) and latest bundler gem (2.7.2) with jemalloc and yjit support:

    - role: ruby

An example showing options you can set (NOTE: checksum is for xz file extension for versions > 3.0, and bz2 for lower versions).

    - role: ruby
      ruby_major_minor: 3.4
      ruby_version: 3.4.5
      ruby_version_checksum: sha256:7b3a905b84b8777aa29f557bada695c3ce108390657e614d2cc9e2fb7e459536
      ruby_bundler_version: 2.7.2

## License

MIT
