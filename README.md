# Docker

Role to install Oracle SQL Developer on an Ubuntu box

## Requirements

After downloading the role use the url on `eclipse/files/eclipse-jee-mars-2-linux-gtk-x86_64.tar.gz.download` to download the installer and make sure its name matches the variable `ECLIPSE_BUNDLE`.

##Role Variables

 * `ECLIPSE_BUNDLE` - the eclipse bundle version, defaults to `eclipse-jee-mars-2-linux-gtk-x86_64.tar.gz`.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: eclipse, ECLIPSE_BUNDLE: eclipse-jee-mars-2-linux-gtk-x86_64.tar.gz }

## License

MIT

## Author Information

Marco Shimomoto
