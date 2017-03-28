# Ansible role for ruby

This builds ruby on recent ubuntu.

## Example playbook

Basic setup which installs the latest ruby:

    - role: ruby

Here is an example to specify the version:

    - role: ruby
      ruby_major_minor: 2.4
      ruby_version: 2.4.1

## License

MIT

