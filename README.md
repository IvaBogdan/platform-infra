# MicroLab - platform infra

## Start
1) Copy env:
    - cp .env.example .env
    - set MSSQL_SA_PASSWORD to a strong password

2) Run:
    - docker compose up -d

3) Check:
    - docker compose ps

## Useful URLs
- RabbitMQ UI: http://localhost:15672 (guest/guest)
- Seq: http://localhost:5341
- Jaeger: http://localhost:16686

## SQL Server connection string (local)
Server=localhost,1433;User ID=sa;Password=<your>;TrustServerCertificate=True;Encrypt=False;
