# CrackMapExec-MachineAccountQuota
CrackMapExec module that retrieves the "MachineAccountQuota" domain-level attribute.

## Install

```shell
cd /path/to/crackmapexec/modules/
wget https://raw.githubusercontent.com/ShutdownRepo/CrackMapExec-MachineAccountQuota/main/MachineAccountQuota.py
```

## Usage

```shell
cme ldap domain_controller -d domain.local -u someuser -p somepassword -M maq
```