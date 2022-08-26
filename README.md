# Dictionary_API
Made API call to wordnik to get required definitions for a particular searched word

# Instructions
  1. You need to do npm install in respective file folder to install required dependencies
  2. Do npm start to run the project
  3. You will also need to generate a wordnik api of your own and add to .env file for project to run
     ### In env do
      REACT_APP_API_URL=https://api.wordnik.com/v4/word.json/
      REACT_APP_API_URL_LATTER=/definitions?limit=200&includeRelated=true&useCanonical=true&includeTags=false&api_key=<Your key>

# Limitations
  1. Better CSS design needed
  2. Need solution for xml tags recieved in data
