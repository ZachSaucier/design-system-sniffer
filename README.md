# Design System Sniffer

React based style sniffer. MVP used for demo at [RenderATL 2025](https://www.renderatl.com/)

## Setup

In the project directory, run 

```
npm i
```

## Running the sniffer

```
npm run analyze {website_url}
```

where `website_url` is formatted like `https://example.com`.

> **Note:** This project scrapes a website's styles with Puppeteer. It will timeout if the website disallows scrapping or if the request exceeds a minute.

After analysis is complete, open local React app by running:

```
npm run dev
```

This runs the app in the development mode.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
