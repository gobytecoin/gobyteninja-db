# GoByte Ninja Database (gobyteninja-db)
forked from dashninja-db By Alexandre (aka elbereth) Devilliers

Check the running live website at https://masternodes.gobyte.network

This is part of what makes the GoByte Ninja monitoring application.
It contains:
- Database structure (MySQL)

## Requirement:
* You will need a running MySQL with a GoByte Ninja database and user.

## Optional:
* A user for the public API with only SELECT ability.
* A user for the private API with SELECT/INSERT/UPDATE ability.

## Install:
* Import database structure in your MySQL server

## Update:
* Check your database version from cmd_config
* Use the each corresponding script in /update to update from that version until you reach the last version
