# davedkg-jets-template

## Local Setup

```bash
$ brew install postgresql yarn
$ bundle && yarn
$ cp .env.development.sample .env.development && nano .env.development
$ jets db:create db:migrate
$ foreman start -f Procfile.dev
$ open http://localhost:8888/
```

#### Rebrand App

| File | Change |
| --- | --- |
| config/application.rb | config.project_name |
| .env.development | database name |
| .ruby-gemset | gemset name |