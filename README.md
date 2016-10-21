# Role Name: Jboss

An Ansible Role that installs Jboss on RedHat/CentOS.

## Requirements

## Role Variables

### `defaults/main.yml`

* `jboss_dependencies:`

        - java-1.6.0-openjdk
        - unzip
* `jboss_src_url : "http://127.0.0.1"`
* `jboss_location: "/opt"`
* `jboss_packages: "jboss-6.1.0.Final"`
* `jboss_java_home: "/usr/lib/jvm/jre-1.6.0-openjdk.x86_64/"`
* `jboss_db_user: "jboos"`
* `jboss_db_password: "jboss"`
* `jboss_db_url: "jdbc:mysql://127.0.0.1:3306/jboss"`

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Install Jboss.
      hosts: servers
      remote_user: root
      roles:
        - role: ansible-role-jboss

## Author Information

z
