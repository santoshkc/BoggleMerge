# How to install?
1. Clone the following repo and move to project folder: 
>>> git clone https://github.com/santoshkc/BoggleMerge.git
2. Initialize all submodules 
>>> git submodule update --init --recursive --remote
3. Update all files and checkout to master
>>> git submodule foreach git pull origin master   
>>> git submodule foreach git checkout master
4. Move to ruby_rails_dictionary_api directory and install dependencies using **bundle install**  
5. Move to SimpleBoggle and install dependencies using **npm install**
6. Run **npm test** to run test cases
7. Run **npm start** to run front end.
