---
title: MySQL
permalink: /config/databases/mysql
---

## Environment Variables

| Environment Variable | Description                                  | Possible Values           |
| -------------------- | -------------------------------------------- | ------------------------- |
| `CUBEJS_DB_HOST`     | The host URL for a database                  | A valid database host URL |
| `CUBEJS_DB_PORT`     | The port for the database connection         | A valid port number       |
| `CUBEJS_DB_NAME`     | The name of the database to connect to       | A valid database name     |
| `CUBEJS_DB_USER`     | The username used to connect to the database | A valid database username |
| `CUBEJS_DB_PASS`     | The password used to connect to the database | A valid database password |

## SSL

To enable SSL-encrypted connections between Cube.js and the source database, set
the `CUBEJS_DB_SSL` environment variable to `true`. Cube.js can also be
configured to use custom connection settings. For example, to use a custom CA
and certificates, you could do the following:

```dotenv
CUBEJS_DB_SSL_CA=/ssl/ca.pem
CUBEJS_DB_SSL_CERT=/ssl/cert.pem
CUBEJS_DB_SSL_KEY=/ssl/key.pem
```

You can also set the above environment variables to the contents of the PEM
files; for example:

```dotenv
CUBEJS_DB_SSL_CA="-----BEGIN CERTIFICATE-----
MIIDDjCCAfYCCQCN/HhSZ3ofTDANBgkqhkiG9w0BAQsFADBJMQswCQYDVQQGEwJV
SzEMMAoGA1UECgwDSUJNMQ0wCwYDVQQLDARBSU9TMR0wGwYDVQQDDBRhaW9zLW9y
Y2gtZGV2LWVudi1DQTAeFw0yMTAyMTUyMzIyMTZaFw0yMzEyMDYyMzIyMTZaMEkx
CzAJBgNVBAYTAlVLMQwwCgYDVQQKDANJQk0xDTALBgNVBAsMBEFJT1MxHTAbBgNV
BAMMFGFpb3Mtb3JjaC1kZXYtZW52LUNBMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8A
MIIBCgKCAQEAyhYY9+4TduTsNRh/6MaRtE59j8HkAkoQYvNYZN7D1j1oV6yhzitn
oN4bD+HiQWe4J3mwAaJOAAJRCkIVyUXxwZUCPxGN/KVha/pcB8hN6LHfI6vInixp
U9kHNYWWBn428nMeMqts7yqly/HwG1/qO+j4178c8lZNS7Uwh76y+lAEaIkeBipq
i4WuCOiChFc/sIV7g4DcLKKbqzDWtRDjbsg7JRfsALO5gM360GrNYkhV4C5lm8Eh
ozNuaPhS65zO93PMj/3UTyuctXKa7WpaHJHoKZRXAuOwSamvqvFgIQ0SSnW+qcud
fL3GAPJn7d065gh7JvgcT86v7WWBiUNs0QIDAQABMA0GCSqGSIb3DQEBCwUAA4IB
AQCzw00d8e0e5AYZtzIk9hjczta7JHy2/cwTMv0opzBk6C26G6YZww+9brHW2w5U
mY/HKBnGnMadjMWOZmm9Vu0B0kalYY0lJdE8alO1aiv5B9Ms/XIt7FzzGtfv9gYJ
cw5/nzGBBMJNICC1kVLnzzlllLferhCIrczDyPcu16o1Flc7q1p8AbwQpC+A2I/L
8nWlFeHZ+watLtQ1lF3qDzzCumPHrJqAGmlp0265owCM8Q5zv8AL5DStIZvtexrI
JqbwLdbA8smyOFRwCckOWcWjnrEDjO2e3NLWINbB7Z4ZRviZSEH5UZlDLVu+ahGV
KmZIuh7+XpXzJ1MN0SBZXgXH
-----END CERTIFICATE-----"
```

For a complete list of SSL-related environment variables, consult the [Database
Connections section of the Environment Variables Reference][ref-env-var].

## Notes

### Local/Docker

To connect to a local MySQL database using a Unix socket, use
`CUBEJS_DB_SOCKET_PATH`. When doing so, `CUBEJS_DB_HOST` will be ignored.

You can connect to an SSL-enabled MySQL database by setting `CUBEJS_DB_SSL` to
`true`. All other SSL-related environment variables can be left unset. See
[Enabling SSL][self-ssl] for more details.

[ref-env-var]: /reference/environment-variables#database-connection
[self-ssl]: #ssl
