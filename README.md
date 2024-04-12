# Jee Mains Marks Calculator (2024)

## Usage
You can calculate your marks by saving a copy of your responses as an html file, and uploading the file in the calculator

## Answerkeys
The answerkeys.js file contains answer keys as js objects

### Generating new answerkeys
To generate new answerkeys, use the parseAnswerKey function present in main.js. Run it when on the answer key page provided by NTA. It will provide you with a js object representing the answerkey. Place this object in answerkeys.js and update the getAnsKey function in main.js

## Proxies
proxies.js contains a proxy variable, you can change it however you will also need to modify fetchResponseSheet in main.js accordingly  
The default proxies are https://github.com/timepassuser/corsproxy, currently hosted on vercel and https://github.com/timepassuser/corsproxy-worker, a cloudflare worker.

##### Hosted on https://timepassuser.github.io/Jee-Mains-Marks-Calculator/
