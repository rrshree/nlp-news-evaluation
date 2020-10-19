# Evaluate a News Article with Natural Language Processing

Front End Web Developer Nanodegree program - Project 4.

Web tool that allows users to run Natural Language Processing (NLP) on articles or blogs found on other websites. When a user submits a URL of an article, the web page then displays sentiment analysis returned from [meaningcloud API](https://www.meaningcloud.com/products/sentiment-analysis), based on the contents of the article.

## Build Tools

- HTML
- CSS
- JavaScript
- Node
- Express
- Webpack
- meaningcloud API
- Jest
- Workbox

## Installation

```
npm install
```

-- Sign up for an API key at [meaningcloud.com](https://www.meaningcloud.com/developer/create-account)

-- Configure environment variables using dotenv package

1. Install the dotenv package
   `npm install dotenv`
2. Create a new `.env` file in the root of your project
3. Fill the `.env` file with your API key like this:
   `API_KEY=**************************`

-- Start the project

|       Command        |    Action     |
| :------------------: | :-----------: |
| `npm run build-prod` | Build project |
|     `npm start`      |  Run project  |

4. Open browser at http://localhost:8081/
