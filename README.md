![](https://img.shields.io/badge/Microverse-blueviolet)

# CLI-Blog-App

An blog app which operates purely from the CLI (Command Line Interface) allowing users to register, then post articles and also comment other user's posts.

![Data entries](/app/assets/images/Data-entries.png?raw=true "Data entries")

This project is an exercise in active record (the M in MVC - the model - which is the layer of the system responsible for representing business data and logic): model creation and their association.

## Built With
*  Ruby
*  Rails
*  rubocop


## Getting Started

To get a local copy up and running follow these simple steps, then follow the instructions on [Building with Active Record](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby-on-rails/lessons/building-with-active-record-ruby-on-rails).


### Prerequisites
 *  Ruby
 *  Rails
 *  yarn
 *  SQLite3
 *  Node.js


### Setup and Install

* Open your terminal - Windows: `Win + R`, then type cmd | Mac: `Command + space`, then type Terminal
* Navigate to a directory of your choosing using the cd command
* Run this command in your OS terminal: `git clone git@github.com:German-Cobian/CLI-Blog-App.git` to get a copy of the project.
* Navigate to the project's directory using the `cd` command
* Run `rails webpacker:install` to configure Webpacker for your environment
* Install dependencies by running `bundle install`
* Migrate the database to your environment by running `rails db:migrate`
* Execute rails console to load the development environment by running `rails console` or `rails c` for short.
* Play around with the console by adding users, and then posts and also comments for each post under various users
* End the rails console environment by running `exit`


### Usage

All actions are executed from the Ruby Console. Users can be created as long as some validations are committed (Name must be at least 2 characters long, email 9 characters long. and password 8 characters long, and all must be unique in the whole site). Each User can post an unlimited amount of posts. Every Post has a Title (at least 2 chars long) and a Body (at least 4 chars long and 2000 chars maximum) Each Post can have an unlimited amount of Comments.


## Authors

👤 **Promise Johnson**

* GitHub: [promise-J](https://github.com/promise-J)
* Twitter: [@twitterhandle](https://twitter.com/Promise94353263)
* LinkedIn: [LinkedIn](https://www.linkedin.com/in/promise-chiemela-788887142)

👤 **German Cobian**

* GitHub: [@German-Cobian](https://github.com/German-Cobian)
* Twitter: [@GermanCobian1](https://twitter.com/GermanCobian1)
* LinkedIn: [@german-cobian](https://www.linkedin.com/in/german-cobian/)


## 🤝 Contributing

Contributions, issues, and feature requests are welcome!


## Show your support

Give a ⭐️ if you like this project!


## Acknowledgments

Guidelines for this project supplied by [The Odin Project](https://www.theodinproject.com/lessons/ruby-on-rails-micro-reddit)


## 📝 License

This project is [MIT](https://github.com/German-Cobian/CLI-Blog-App/blob/main/LICENSE) licensed.
