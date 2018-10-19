# Ansible role for ruby

This builds ruby on recent ubuntu.

## Example playbook

Basic setup which installs the latest ruby:

    - role: ruby

Here is an example to specify the version:

    - role: ruby
      ruby_major_minor: 2.5
      ruby_version: 2.5.1
      ruby_version_checksum: sha256:0f5d20f012baca865381a055e73f22db814615fee3c68083182cb78a4b3b30cb

## License

MIT

