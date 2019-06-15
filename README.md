# Ansible role for ruby

This builds ruby on recent Ubuntu LTS or CentOS.

## Example playbook

Basic setup which installs the latest ruby and latest bundler gem:

    - role: ruby

How to specify the ruby version:

    - role: ruby
      ruby_major_minor: 2.5
      ruby_version: 2.5.1
      ruby_version_checksum: sha256:0f5d20f012baca865381a055e73f22db814615fee3c68083182cb78a4b3b30cb

How to specify a specific bundler version:

    - role: ruby
      ruby_bundler_version: 2.0.1

## License

MIT
