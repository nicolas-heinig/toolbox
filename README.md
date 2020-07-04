# toolbox

This is my toolbox 🧰

In this repository I keep a list of various software pieces that I like to use.

## Contents

- [Gems](#gems)
- [Data Stores](#data-stores)
- [Terminal](#terminal)
- [Editor](#editor)
- [Dev tools](#dev-tools)
- [Monitoring](#monitoring)
- [Productivity](#productivity)
- [Security](#security)
- [Graphics](#graphics)

## Gems

- [rails](https://github.com/rails/rails) - My favourite ruby framework for many years. I use it every day on the job.
- [sinatra](https://github.com/sinatra/sinatra) - When I want to try out smaller web applications, Sinatra is usually my choice. It's very lightweight, but can be enhanced with many many plugins.
- [hanami](https://github.com/hanami/hanami) - Another framework that I experimented with. I like that it has some of my favourite tools baked in, for example rspec and the interactor pattern.
- [rspec](https://github.com/rspec/rspec) - This is the testing framework of my choice. Whether I write unit tests or web acceptance tests with capybara, RSpec gets the job done. [Effective Testing with RSpec 3](https://pragprog.com/titles/rspec3/) helped me a lot to get to know the tool.
- [interactor](https://github.com/collectiveidea/interactor) - When the business logic goes bigger, I like to organize it in _interactors_, so that I can keep my controllers slim and my models focused on DB interactions. The gem provides a common interface and other helpers.
- [guard](https://github.com/guard/guard) - To automate tasks that should be run whenever I save a file, I use guard. It runs my specs and rubocop every hour at least 100 times while developing.
- [rubocop](https://github.com/rubocop-hq/rubocop) - The standard linter for the ruby world. It helps a lot to follow the [Ruby Style Guide](https://rubystyle.guide/). After I worked in a project that ran without rubocop for 2 years, I know how much value you get from it.
- [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) - If I can use rails to write a one-liner validation, why shouldn't I be able to use a one-line test for that?
- [factory-bot](https://github.com/thoughtbot/factory_bot) - I use `FactoryBot` to generate model instances or their attributes for my specs.
- [database_cleaner](https://github.com/DatabaseCleaner/database_cleaner) - Everything that I write into the DB while testing needs to be cleaned up afterwards. This tool does that for me.
- [faker](https://github.com/faker-ruby/faker) - I am kind of bad when naming test data. `Faker` helps me to generate more sane names, adresses, movie titles and much more.
- [byebug](https://github.com/deivid-rodriguez/byebug) - The debugger of my choice. When I need more fancy output, I use [pry-byebug](https://github.com/deivid-rodriguez/pry-byebug).
- [devise](https://github.com/heartcombo/devise) - When I need to introduce authentication to my applications, Device is my tool of choice. It is very powerful, but you can scope out things you don't need.
- [geocoder](https://github.com/alexreisner/geocoder) - This helps a lot when you need to work with location services. It features many APIs and integrates seamlessly with my default stack.

## Data Stores

- [mysql](https://www.mysql.com/) - I am most familiar with using MySQL as a datastore.
- [postgresql](https://www.postgresql.org/) - When I run own projects on heroku, I tend to use postgres, as the integration on heroku side is very advanced.
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

- [Visual Studio Code](https://github.com/microsoft/vscode) - VS Code is the editor of my choice. I chose it mainly because of its UI and its extensibility. Below I list my top 5 extensions.

  - [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) - I use `Material Theme Darker High Contrast`.
  - [endwise](https://marketplace.visualstudio.com/items?itemName=kaiwood.endwise) - A must-have for every Ruby Developer. It closes `do...end` blocks for you.
  - [Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame) - This shows the `git blame` output for the current line in the status bar.
  - [Rails Run Specs](https://marketplace.visualstudio.com/items?itemName=noku.rails-run-spec-vscode) - With this extension you are able to quickly run the specs for the current file or line with one keystroke.
  - [Ruby Solargraph](https://marketplace.visualstudio.com/items?itemName=castwide.solargraph) - Provides Go-To-Definition and intellisense for Ruby Projects.

- [IntelliJ](https://www.jetbrains.com/idea/) - Whenever I need to code on a JVM language like Java or Scala, I use IntelliJ. I am currently working through [Head First Design Patterns](https://www.oreilly.com/library/view/head-first-design/0596007124/) by coding along the examples.

## Dev tools

- [git](https://github.com/git/git) - Must have. I like to squash merge feature branches into the master for a clean history.
- [homebrew](https://brew.sh/) - I work on MacOS. Homebrew provides the necessary packages for everything.
- [docker](https://www.docker.com/) - We run our infrastructure based on docker. But I also like to use it for development to run applications or backing services.
- [heroku](https://heroku.com) - When I need to host my personal projects, I use herokus free tier. I like to deploy by just pushing to a special git source.

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

## Graphics

- [Skitch](https://evernote.com/intl/de/products/skitch) - Quickly take a screenshot and use arrows, boxes, etc. to highlight important elements.
- [yEd](https://www.yworks.com/products/yed) - For various visualizations yEd is a easy to use but powerful tool. You can use it for flowcharts, diagrams and many others.
