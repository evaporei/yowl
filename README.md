<p align="center">
  <a href="https://github.com/otaviopace/yowl">
    <img src="https://user-images.githubusercontent.com/15306309/45008498-7590fb80-afd9-11e8-8a76-fccf7c58a414.gif" alt="yowl_gif" >
  </a>
</p>

<h1 align="center">yowl</h1>

> Twitter clone in Rails 5

## What do you kneed on your computer

- Ruby
- Ruby Gem "Bundler"
- Ruby Gem "Rails"

Note: if you have `arch linux`, just like me, for setup I've just used:

Install `ruby`:

```shell
sudo pacman -Sy ruby
```

Install `rails` and `bundler`:

```shell
yaourt -Sy ruby-rails
# or yay
yay -Sy ruby-rails
```

* Ruby version used: *2.5.3*, but the `Gemfile` is setup to work with any version bigger than *2.5* :slightly_smiling_face:

## How to run

### Install dependencies:

```shell
bundle install
```

### Run migrations:

```shell
rails db:migrate
```

### Run the project:

```shell
rails server
```
