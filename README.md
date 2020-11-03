# Backend Assignment to write data to Excel

## Writing Data to Excel

Use the Github api and based on command line input, pass query parameter to the below API:

[Github API](https://api.github.com/search/repositories?q=tetris+language:javascript&sort=stars&order=desc)
User input will replace **tetris** in the above url.

- Read the above data
- Write data for each repo to Excel sheet
- only add headers - homepage, size, language, watchers, description, name, full_name
- Paginate on all records and write to Excel
