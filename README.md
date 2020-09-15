# Interactive-Terminal-Spawned-via-Python
Identifies when a terminal (tty) is spawned via Python. Attackers may upgrade a simple reverse shell to a fully interactive tty after obtaining initial access to a host.

Example :-> python -c 'import pty; pty.spawn("/bin/bash")'

where : 

python : script language as we all know

-c : cmd : program passed in as string (terminates option list), should be in ' '.

pty : The Pseudo-terminal utility module pty is defined to handle pseudo-terminal concepts.

spawn : Spawn is a python package that allows users to concisely specify and execute a large number of tasks with complex and co-dependent input parameter variations.

/bin/bash : is the most common shell used as default shell for user login of the linux system.


