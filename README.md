<!-- Add CI and code coverage badges here. Samples included below. -->
[![CI](https://github.com/ansible-collections/cisco.cvd_compute/workflows/CI/badge.svg?event=push)](https://github.com/ansible-collections/cisco.cvd_compute/actions) [![Codecov](https://img.shields.io/codecov/c/github/ansible-collections/cisco.cvd_compute)](https://codecov.io/gh/ansible-collections/cisco.cvd_compute)

# Ansible Validated Content Collection for Cisco UCS Compute 
<!-- Describe the collection and why a user would want to use it. What does the collection do? -->
This collection includes a variety of validated Ansible roles to automate and manage Day-2 use cases with Cisco UCS.

## Dependencies
This collection leverages Ansible Certified collection of modules for Cisco Intersight [Cisco Intersight API](https://intersight.com/apidocs/introduction/overview/) to access the Intersight Management Information Model.


## Tested with Ansible

<!-- List the versions of Ansible the collection has been tested with. Must match what is in galaxy.yml. -->

## Using this collection

<!--Include some quick examples that cover the most common use cases for your collection content. It can include the following examples of installation and upgrade (change NAMESPACE.COLLECTION_NAME correspondingly):-->

### Installing the Collection from Ansible Galaxy

Before using this collection, you need to install it with the Ansible Galaxy command-line tool:

```bash
ansible-galaxy collection install cisco.cvd_compute
```

You can also include it in a `requirements.yml` file and install it with `ansible-galaxy collection install -r requirements.yml`, using the format:

```yaml
---
collections:
  - name: cisco.cvd_compute
```

Note that if you install the collection from Ansible Galaxy, it will not be upgraded automatically when you upgrade the `ansible` package. To upgrade the collection to the latest available version, run the following command:

```bash
ansible-galaxy collection install cisco.cvd_compute --upgrade
```

You can also install a specific version of the collection, for example, if you need to downgrade when something is broken in the latest version (please report an issue in this repository). Use the following syntax to install version `0.1.0`:

```bash
ansible-galaxy collection install cisco.cvd_compute:==0.1.0
```

See [using Ansible collections](https://docs.ansible.com/ansible/devel/user_guide/collections_using.html) for more details.

## Release notes

See the [changelog](https://github.com/ansible-collections/cisco.cvd_compute/tree/main/CHANGELOG.rst).

## More information

* [Cisco UCS solutions team repositories](https://github.com/ucs-compute-solutions)
* [Cisco Intersight Ansible collection](https://galaxy.ansible.com/cisco/intersight)
* [Ansible user guide](https://docs.ansible.com/ansible/devel/user_guide/index.html)
* [Ansible developer guide](https://docs.ansible.com/ansible/devel/dev_guide/index.html)
* [Ansible collections requirements](https://docs.ansible.com/ansible/devel/community/collection_contributors/collection_requirements.html)
* [Ansible community Code of Conduct](https://docs.ansible.com/ansible/devel/community/code_of_conduct.html)
* [The Bullhorn (the Ansible contributor newsletter)](https://docs.ansible.com/ansible/devel/community/communication.html#the-bullhorn)
* [Important announcements for maintainers](https://github.com/ansible-collections/news-for-maintainers)
