MariaDB chart
---
MariaDB is a community-developed, commercially supported fork of the MySQL relational database management system (RDBMS), intended to remain free and open-source software under the GNU General Public License

for install: 

```bash
helm install mariadb sandbox/mariadb
```

with credentials:
```bash
helm install mariadb sandbox/mariadb --set=mariadb.root.password=password,mariadb.database.user=user,mariadb.database.password=userpassword
```