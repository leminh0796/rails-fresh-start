# Let's start

A Rails blank project with newest tools setup, included hot reload view. 

| Tools | Version |
| ------ | ------ |
| Ruby | 3.0.2 |
| Rails | 7.0.2.2 |
| Database | PostgreSQL (config/database.yml) |
| Stylesheet | Tailwind CSS 3 |
| Javascript builder | esbuild |
| Hot Reload | Yes |

### Normal steps
--------------------------------
- Requirements: ruby, nodejs, yarn, postgresql installed.
- Run project:
```sh
$ rails db:create
$ bundle install
$ yarn install
$ bin/dev
```

### Docker steps
--------------------------------
- Requirement: docker installed.
- Edit host in config/database.yml to 'db'
- Run project:
```sh
$ docker-compose up
```
