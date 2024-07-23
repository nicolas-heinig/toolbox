# toolbox

This is my toolbox 🧰

In this repository I keep a list of various software pieces that I like to use.

## Contents

- [Languages](#languages)
- [Frameworks](#frameworks)
- [Libraries](#libraries)
- [Data Stores](#data-stores)
- [Terminal](#terminal)
- [Editor](#editor)
- [Dev tools](#dev-tools)
- [Monitoring](#monitoring)
- [Productivity](#productivity)
- [Security](#security)

## Languages

- [ruby](https://github.com/ruby/ruby) - My go to language and the one I do best. Focus on simplicity and productivity. Its elegant syntax is natural to read and easy to write, but I know about its limitations and started to look around into other languages.
- [go](https://github.com/golang/go) - And I found go. Its much more low level, which enticed me a lot. Did some experimenting and built some CLI tools, but I am still waiting production experience.
- [rust](https://github.com/rust-lang/rust) - But I also found rust. Similiar to go, only did some pet projects with it, but the ecosystem exites me a lot.
- javascript / preferably [typescript](https://github.com/microsoft/TypeScript) - The standard for web development. Always delighted how versatile it is. I prefer its statically typed superset typescript that brings safety and other features to the table.
- bash - Adding it here for completeness, as I like to do a lot of shell scripting. I build short cuts, small CLIs to easy my day to day work. (But not advanced as in [hacker-scripts](https://github.com/NARKOZ/hacker-scripts?tab=readme-ov-file#hacker-scripts)

## Frameworks

- [rails](https://github.com/rails/rails) - My favourite ruby framework for many years. I use it every day on the job.  Ran it at scale and for pet projects.
- [sinatra](https://github.com/sinatra/sinatra) - When I want to try out smaller web applications, Sinatra is usually my choice. It's very lightweight, but can be enhanced with many many plugins.
- [hanami](https://github.com/hanami/hanami) - Another framework that I experimented with. I like that it has some of my favourite tools baked in, for example rspec and the interactor pattern.
- [react.js](https://github.com/facebook/react) - The web framework I am most familiar with (and also a very popular one). Started looking into it in 2017, rediscovered in 2024 and was suprised how mature it got. I feel free comfortable around it.
- [express.js](https://github.com/expressjs/express) - Minimal, flexible, node.js. Sometimes this is what you need.

## Libraries

- [rspec](https://github.com/rspec/rspec) - This is the testing framework of my choice. Whether I write unit tests or web acceptance tests with capybara, RSpec gets the job done. [Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/) helped me a lot to get to know the tool.
- [interactor](https://github.com/collectiveidea/interactor) - When the business logic goes bigger, I like to organize it in _interactors_, so that I can keep my controllers slim and my models focused on DB interactions. The gem provides a common interface and other helpers.
- [guard](https://github.com/guard/guard) - To automate tasks that should be run whenever I save a file, I use guard. It runs my specs and rubocop every hour at least 100 times while developing.
- [rubocop](https://github.com/rubocop-hq/rubocop) - The standard linter for the ruby world. It helps a lot to follow the [Ruby Style Guide](https://rubystyle.guide/). After I worked in a project that ran without rubocop for 2 years, I know how much value you get from it.
- [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - If I can use rails to write a one-liner validation, why shouldn't I be able to use a one-line test for that?
- [factory-bot](https://github.com/thoughtbot/factory_bot) - I use `FactoryBot` to generate model instances or their attributes for my specs.
- [faker](https://github.com/faker-ruby/faker) - I am kind of bad when naming test data. `Faker` helps me to generate more sane names, adresses, movie titles and much more.

## Data Stores

- [mysql](https://www.mysql.com/) - I am most familiar with using MySQL as a datastore.
- [postgresql](https://www.postgresql.org/) - When I run own projects on heroku, I tend to use postgres, as the integration on heroku side is very advanced. Grown more familiar in the last months.
- [redis](https://redis.io/) - For Caching purposes or projects where I don't need a full relation database setup, I use redis.

## Terminal

- [zsh](https://github.com/zsh-users/zsh) - My go-to shell is zsh.
- [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) - Enables easy customization of the shell. Below I list the top 5 of my favorite plugins.

  - [git](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/git) - Autocomplete and aliases for git commands.
  - [docker](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/docker) - Autocomplete for docker commands.
  - [rake](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/rake) - Reads out our Rakefile and tasks and autocompletes the command.
  - [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Syntax highlighting in the shell. I like that it shows the command in red when it does not exist.
  - [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - Suggests commands from your history again. Very helpful if you are keen to smash the arrow up button over and over again.

- [iterm](https://iterm2.com/) - The terminal replacement I use. I enjoy splitting the panes and getting notifications when a long-running command finally finishes.
- [thefuck](https://github.com/nvbn/thefuck) - You did a small typo? No problem. Just type into the console what you might whisper to yourself and let the magic happen.
- [tldr](https://github.com/tldr-pages/tldr) - This nice command gives you a small summary of typical usages for the most commands.

## Editor

- [neovim](https://github.com/neovim/neovim) - I belong to the cult. My configuration is built from scratch, but hidden in my private dotfiles repository.
- [IntelliJ](https://www.jetbrains.com/idea/) - Whenever I need to code on a JVM language like Java or Scala, I use IntelliJ.

## Dev tools

- [git](https://github.com/git/git) - Must have. I like to squash merge feature branches into the master for a clean history.
- [homebrew](https://brew.sh/) - I work on MacOS. Homebrew provides the necessary packages for everything.
- [docker](https://www.docker.com/) - We run our infrastructure based on docker. But I also like to use it for development to run applications or backing services.

## Monitoring

- [Grafana](https://github.com/grafana/grafana) - Grafana is my choice for metric visualization.
- [Graphite](https://graphiteapp.org/) - I use Graphite to store metrics for Grafana.
- [statsd](https://github.com/statsd/statsd) - StatsD is a small metric collector that collects metrics as UDP packages and flushes them into Graphite. There are libraries for many programming languages.
- [Sentry](https://sentry.io/) - Simple free exception logging for various tech stacks.

## Productivity

- [Microsoft To Do](https://todo.microsoft.com/) - I organize my tasks in Microsoft To Do using the [Getting Things Done Methodology](https://gettingthingsdone.com/).
- [Google Keep](https://www.google.de/keep/) - The note taking application of my choice. Notes are easy to write, and easy to organize with labels. The only thing missing for me is markdown support.

## Security

- [1Password](https://1password.com/) - I use 1Password as my password manager. It stores not only the passwords for various websites, but also passwords that I share with my team inside a shared vault.
