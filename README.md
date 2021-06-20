# simple-website-with-blog

> A simple website with a blog

`simple-website-with-blog` is a simple [Node.js](https://nodejs.org/) web application for static content that includes a blog.

## Goals

- An easy way to create a simple, secure website with a blog
- Support for text-based blog formats
- Ordering of posts by publish date or content date
- Simple post format that separates content and metadata
## Structure

- `/app.js` Entry point for the application, configures the server and static content
- `/blog.js` Implementation of the blog, archives, tags, search, and RSS
- `views\partials` Environment variables and ejs files used to control basic behavior
- `views` Blog layout code shared by the website
### First look
![sample]()
### Posting section
![sample2]()
### Home page after posting
![sample3]()
### Complete post looks like
![sample4]()

## Instructions

1. Install Node.js version 10+
1. Fork and clone repository`
1. `npm install`
1. `npm app.js`
1. Open <http://localhost:3000/> and verify

## Dependencies

| Project      | Home Page                                    |
|--------------|----------------------------------------------|
| Express      | <https://expressjs.com/>                     |
| ejs          | <https://ejs.co/>                            |
| bodyParser   | <https://www.npmjs.com/package/body-parser>  |
| lodash       | <https://lodash.com/>                        |

## Contributing

- Open issue, discuss proposal
- Fork and clone repository
- Change code and update tests
- `npm test`
- `npm run lint`
- Review changes
- Send pull request

## License

[MIT](LICENSE)