# Administration

## Users
Admin User:

    CREATE USER admin WITH PASSWORD 'password' WITH ALL PRIVILEGES

Standard:

    CREATE USER <username> WITH PASSWORD 'password'
    GRANT [READ,WRITE,ALL] ON <database_name> TO <username>

    show users

## Retention Policies
    SHOW RETENTION POLICIES ON sysstat

Change:
    ALTER RETENTION POLICY <retention_policy_name> ON <database_name> DURATION <duration> REPLICATION <n> [DEFAULT]

Duration:
- m minutes
- h hours
- d days
- w weeks
