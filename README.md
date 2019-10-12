ansible-role-colors
=========

A role used to register variables with colorcodes for Bash.

Requirements
------------

A ANSI terminal.

Role Variables
--------------

None

Dependencies
------------

None

Example Usage
----------------

As task:
    - pause:
        prompt: |
          I {{  yamlcolors.Red }}love{{  yamlcolors.NC }} you!
        seconds: 0


In a sh-script-template:
    echo -e "I {{ bashcolors.Red }}love{{ bashcolors.NC }} you!"

License
-------

CC-BY-4.0

Author Information
------------------

tvartom

