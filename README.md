# fastify-mysql2

This is a fork of Fastify MySQL connection plugin, with this you can share the same MySQL connection pool in every part of your server. Under the hood the [mysql2](https://github.com/sidorares/node-mysql2) is used, the options that you pass to `register` will be passed to the MySQL pool builder.

