# About
Boggle Game with frontend developed in React and backend in Ruby on Rails.

## Features
* 4x4 game board
* User can type the words which they think they found.
* Client side validation to check word is valid. Server side validation to check if word is actually available in dictionary.  
If both validation is successfull, then word in added to successful word list.
* Error displayed if word is invalid.
* Successfully matched words with corresponding score are always shown in table.
* When timer runs out, user is no longer allowed to enter word.

## Extra features
* Board letters can be clicked to be used as input.
* At server side, dictionary is loaded in trie datastructure for efficient word lookup.
* Ability to reset game without refreshing browser.
* Ability to pause game(for quick break)

# Instructions to Run
1. Clone the following repo and move to project folder:  
>`git clone https://github.com/santoshkc/BoggleMerge.git`
2. Initialize all submodules  
>`git submodule update --init --recursive --remote`
3. Update all files and checkout to master  
>`git submodule foreach git pull origin master`   
>`git submodule foreach git checkout master`

## For Backend(Ruby on the Rails) 
### Prerequisites
* `Ruby 2.7.1`
* `bundler 2.1.4`
* `Rails 6.0.3.2`

### Steps to run
1. Move to ruby_rails_dictionary_api directory and install dependencies using `yarn` and then `bundle install`
2. Run `rake test` to run test cases.
3. Run `rails server -p 4000` to start backend server(frontend uses hardcoded port 4000)

## For FrontEnd(React)
### Prerequisites
* `React 16.13.1(Created using create-react-app)`

### Steps to run
1. Move to SimpleBoggleApp directory and install dependencies using `npm install`
2. Run `npm test` to run test cases
3. Run `npm start` to run front end.
