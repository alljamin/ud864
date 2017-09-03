API key is specified in the `config.js` what is added to `.gitignore` and not displayed publicly in the GitHub repository.
To run this project:
- create `config.js` in the same directory with the project itself
- define your api key in `config.js` like so:
`var config = {
    api_key : 'YOUR_API_KEY'
}`

Idea is taken based on these examples:
- https://stackoverflow.com/questions/31342359/dynamically-set-googleapi-key
- https://gist.github.com/derzorngottes/3b57edc1f996dddcab25