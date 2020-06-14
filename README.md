# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis serve --dev
```

or manually clone the repo and then run `npm install`.

### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
adonis make:seed
  --env                Set NODE_ENV before running the commands
  --no-ansi            Disable colored output

Available Commands:
  addon                Create a new AdonisJs addon
  install              Install Adonisjs provider from npm/yarn and run post install instructions
  new                  Create a new AdonisJs application
  repl                 Start a new repl session
  seed                 Seed database using seed files
  serve                Start Http server
 key
  key:generate         Generate secret key for the app
 make
  make:command         Make a new ace command
  make:controller      Make a new HTTP or Websocket channel controller
  make:ehandler        Make a new global exception handler
  make:exception       Make a new exception
  make:hook            Make a new lucid model hook
  make:listener        Make a new event or redis listener
  make:middleware      Make a new HTTP or Ws Middleware
  make:migration       Create a new migration file
  make:model           Make a new lucid model
  make:provider        Make a new provider
  make:seed            Create a database seeder
  make:trait           Make a new lucid trait
  make:view            Make a view file
 migration
  migration:refresh    Refresh migrations by performing rollback and then running from start
  migration:reset      Rollback migration to the first batch
  migration:rollback   Rollback migration to latest batch or to a specific batch number
  migration:run        Run all pending migrations
  migration:status     Check migrations current status
 route
  route:list           List all registered routes
 run
  run:instructions     Run instructions for a given module
```
