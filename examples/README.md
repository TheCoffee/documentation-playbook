# Next.js Project

This project is a single page eCommerce system that has been built in Next.js. This web app uses Google Sheets as a backend.

<br>
<div align='center'>
    <img alt="NextJS" src="https://img.shields.io/badge/NextJS-black.svg?style=for-the-badge&logo=next.js&logoColor=white"/>
    <img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
    <img alt="Google API" src="https://img.shields.io/badge/Google_API-%233780F1.svg?style=for-the-badge&logo=java&logoColor=white"/>
    <img alt="Typescript" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"/>
    <img alt="Tailwind CSS" src="https://img.shields.io/badge/tailwind_css-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
    <img alt="Post CSS" src="https://img.shields.io/badge/Post_CSS-1867C0?style=for-the-badge"/>
</div>
<br>

## Getting Started

First, install the project dependencies by running:

```bash
yarn install
```

## Environment variables

Copy over `.env.example` as `.env.local`. If you are running the branch connected to Google sheets (`chronos`), set up your google project & enable the sheetsAPI 👈. Get the Products sheet id, Orders sheet id and API keys from the service account json. Add them to the .env.local file.

-   `GOOGLE_SPREADSHEET_ID_PRODUCT` - Google sheets ID of the products sheet
-   `GOOGLE_SPREADSHEET_ID_ORDER` - Google sheets ID of the orders sheet
-   `GOOGLE_SERVICE_ACCOUNT_CLIENT_EMAIL` - Service account email from the Google project service_account.json
-   `GOOGLE_SERVICE_ACCOUNT_PRIVATE_KEY` - Private key from the Google project service_account.json

## Running the development server

Run the development server using:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.
