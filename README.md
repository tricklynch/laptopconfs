# Laptop Configs
> Ansible for personal use

I reinstall operating systems far too often, commonly back to the same OS. This
will save me time on setting up after each reinstall. Further, when solving a
problem, it's sometimes difficult to remember what steps were taken so it's
difficult to determine what cleanup is needed. Using this repo to configure
everything, cleanup should be as easy as setup.

## Installing / Getting started

Install Ansible and run the playbook

```shell
sudo dnf uninstall ansible
ansible-playbook site.yml
```

This installs ansible, configures the system, and tests that the configurations
worked.

## Features

* Installs a variety of dev-oriented packages
* Configures git, vim, fish, and terminator
* Ensures common executables are in $PATH

## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome.

## Links

- Project homepage: https://github.com/tricklynch/laptopconfs/#todo+use+gh+pages
- Repository: https://github.com/tricklynch/laptopconfs/
- Issue tracker: https://github.com/tricklynch/laptopconfs/issues
  - In case of sensitive bugs like security vulnerabilities, please contact
    p+laptopconfs@tricklynch.org directly instead of using issue tracker.
    We value your effort to improve the security and privacy of this project!
- README.md template: https://raw.githubusercontent.com/jehna/readme-best-practices/master/README-default.md

## Licensing

The code in this project is licensed under the GNU General Public License v3.
