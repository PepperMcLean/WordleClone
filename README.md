# WordleClone
This single page application displays a page where you can play a clone of the popular game Wordle.

# Install Instructions
Clone the repository.
```sh
$ git clone git@github.com:PepperMcLean/WordleClone.git
```
## Navigate to the api folder

Install the dependencies 
```sh
$ bundle install
```
Prepare the Database
```sh
$ rails db:migrate
```
Seed the Database
```sh
$ rails db:seed
```

## Navigate to the front end 

Install the dependencies
```sh
$ npm install
```

## Usage
In the API folder 
Start the server
```sh
$ rails s -p 3001
```
In the front end
```sh
$ npm start
```
The App should automatically open up in your browser.

## Contributing
Bug reports and pull requests are welcome on GitHub at https://github.com/PepperMcLean/WordleClone. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant code of conduct](https://www.contributor-covenant.org/).

## License
[MIT](LICENSE)

## Conduct
Everyone interacting in the WordleCLone project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](CodeOfConduct.md).
