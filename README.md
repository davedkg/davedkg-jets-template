# davedkg-jets-template

## Local Setup

```bash
$ brew install postgresql yarn
$ bundle && yarn
$ foreman start -f Procfile.dev
$ open http://localhost:8888/
```

#### Rebrand App

| File | Change |
| --- | --- |
| .ruby-gemset | gemset name |
| config/application.rb | config.project_name |