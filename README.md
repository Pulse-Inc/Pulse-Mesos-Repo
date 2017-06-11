# Pulse Mesos Framework

## Install

- Add the DCOS Pulse package to your DCOS repository sources:

		dcos package repo add --index=0 Pulse https://github.com/Pulse-Inc/Pulse-Mesos-Repo/archive/1.0.0.zip

- Install the `dcos pulse` subcommand:

		dcos package install pulse --options /etc/pulse-mesos/config.json


