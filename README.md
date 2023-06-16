# MySQL Test Application
[![None](https://charmhub.io/mysql-test-app/badge.svg)](https://charmhub.io/mysql-test-app)

MySQL stack tester charm - this is a simple application used exclusively for integrations test of
[mysql-k8s][mysql-k8s], [mysql][mysql], [mysql-router-k8s][mysql-router-k8s],
[mysql-router][mysql-router], [mysql-bundle-k8s][mysql-bundle-k8s] and
[mysql-bundle][mysql-bundle].

## Relations

This charm implements relations interfaces:
* database
* mysql (legacy)

On using the `mysql` legacy relation interface with either [mysql] or [mysql-k8s] charms, its
necessary to config the database name with:

```shell
> juju config mysql-k8s mysql-interface-database=continuous_writes_database
```

## Actions

Actions are listed on [actions page](https://charmhub.io/mysql-test-app/actions)


[mysql-k8s]: https://charmhub.io/mysql-k8s
[mysql]: https://charmhub.io/mysql
[mysql-router-k8s]: https://charmhub.io/mysql-router-k8s
[mysql-router]: https://charmhub.io/mysql-router?channel=dpe/edge
[mysql-bundle-k8s]: https://charmhub.io/mysql-bundle-k8s
[mysql-bundle]: https://charmhub.io/mysql-bundle

## References

* [MySQL Test App at Charmhub](https://charmhub.io/mysql-test-app)
