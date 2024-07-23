Ansible imports v.s. includes
-----

This is an example that demonstrates the conceptual differences between Ansible imports and includes.

During the execution of site.yml, two playbooks are imported that go on and include or import some tasks.

Those two playbooks show the debug information from the debug.yml playbook, although differently.

Please note that `include_playbook` is not available in Ansible.
