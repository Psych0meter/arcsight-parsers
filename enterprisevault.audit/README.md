# Enterprise Vault Audit parser
For ID-Based DB SmartConnector

## Installation
Configuration folder : EnterpriseVaultAudit

Copy flexagent directory in $ARCSIGHT_HOME$/current/user/agent/

Restart SmartConnector

## Table view example
```
+---------+---------+---------------------+----------+--------------+-----------------+------------------+----------------+---------------------------+-------------+
| AuditID | Status  | AuditDate           | UserName | CategoryName | SubCategoryName | ObjectID         | Vault          | info                      | MachineName |
+---------+---------+---------------------+----------+--------------+-----------------+------------------+----------------+---------------------------+-------------+
|       1 | SUCCESS | 2018-11-14 12:24:36 | TestUser | View         | Information     | 1231861531864351 | d4ze86f45ze6f5 | Description of the action | Machine01   |
+---------+---------+---------------------+----------+--------------+-----------------+------------------+----------------+---------------------------+-------------+
1 row in set (0.00 sec)
```