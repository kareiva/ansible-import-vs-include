Ansible imports v.s. includes
-----

This is an example that demonstrates the conceptual differences between Ansible imports and includes.

During the execution of site.yml, two playbooks are imported that go on and include or import some tasks.

Those two playbooks show the debug information from the tasks.yml playbook, although differently.

Please note that `include_playbook` is not available in Ansible.

### Documentation:

https://learn.redhat.com/t5/RH294-Red-Hat-Linux-Automation/import-tasks-vs-include-tasks/td-p/34982

https://docs.ansible.com/ansible/devel/playbook_guide/playbooks_reuse.html#dynamic-vs-static
