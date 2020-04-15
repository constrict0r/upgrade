Description
--------------------------------------------------------------

Ansible role to apply a system upgrade.

This role performs the following actions:

- Ensure the requirements are installed.

- Ensure the current user can obtain administrative (root) permissions.

- Update the apt cache.

- If the **upgrade** variable is set to *true* or if the **configuration**
  file contains a variable **upgrade** setted to *true*, perform a full system
  upgrade.