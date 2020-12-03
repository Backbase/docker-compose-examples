# Docker compose demos

A set of Docker compose files to demo Backbase docker images and how they can be used

- [Backbase with ActiveMQ](docker-compose.yaml)
- [Backbase with RabbitMQ](rabbitmq/docker-compose.yaml)
- [Backbase with Apache Kakfa](kafka/docker-compose.yaml)
- [Backbase with SQL Server](mssql-server/docker-compose.yaml)
- [Backbase with DBS Lean services](dbs-lean/docker-compose.yaml)
- [Backbase with CX6 and Content Approval services](content-approval/docker-compose.yaml)
- Backbase with Identity 

Update `.env` file for version.

To run nested `docker-compose.yaml` from root:
```
docker-compose -f <path-to-compose-file> up -d
```

## Provisioning Statics

Change `<yourRepoUsername>` and `<yourRepoPassword>` with your Repo credentials in `job.yaml`.
