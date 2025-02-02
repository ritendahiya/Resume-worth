# Resume Worth Calculator

This app estimates the dollar worth of your resume (i.e. how much money you can make with your resume).

This project is built using Next.js and the Mistral API. The content from the resume pdf is extracted by PDF.js.

<img src="resumeworth-demo.gif" alt="app demo" width=600>

## Getting Started

First, duplicate the `.env` file into a new file named `.env.local`. Update the value of your Mistral API key there. To get a key, you need to sign up on https://console.mistral.ai/

The first time you are running this project, you will need to install the dependencies. Run this command in your terminal:

```bash
yarn
```

To start the app, run:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.
