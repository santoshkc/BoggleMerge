# How to install?
1. Clone the following repo and move to project folder: 
>>> git clone https://github.com/santoshkc/BoggleMerge.git
2. Initialize all submodules 
>>> git submodule update --init --recursive --remote
3. Update all files and checkout to master
>>> git submodule foreach git pull origin master   
>>> git submodule foreach git checkout master

## For Backend(Ruby on the Rails) 
1. Move to ruby_rails_dictionary_api directory and install dependencies using **bundle install**
2. Run **rake test** to run test cases.
3. Run **rails server -p 4000** to start backend server(frontend uses hardcoded port 4000)

## For FrontEnd(React)
1. Move to SimpleBoggle and install dependencies using **npm install**
2. Run **npm test** to run test cases
3. Run **npm start** to run front end.
