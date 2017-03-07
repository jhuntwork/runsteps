runsteps
========

A controlled ordered command runner.

What does that mean? It means that given a series of commands, perhaps a
set of shell scripts, and a mechanism for specfying the order of those
commands, runsteps will execute them and monitor them for state and
failure.

Additionally, because of the shared controlling application, each of the
commands may have access to runsteps's shared knowledge about them and
may access this shared data.
