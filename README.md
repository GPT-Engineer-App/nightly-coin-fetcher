# nightly-coin-fetcher

 A Backend serivce, that would call the coinngecko api, every night fetch list of all available token. And then for each of those tokens call the single coin endpoint to get all the relevant info, and then store it. On the next execution, after the list api call, do a diff of only the coins that are new and not already stored. For the new coins call the single api , fetch all the details and then store it.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/nightly-coin-fetcher.git
cd nightly-coin-fetcher
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
