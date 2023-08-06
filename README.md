# Travel-Agent-App

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Mock-Up](#mock-up)
- [Usage](#usage)
- [License](#license)
- [Badges](#badges)

## Description

# User Story

```
As an avid traveler,
I WANT to use a travel agent application
SO THAT I can choose trip packages, plan my own trip, or hire a live agent to plan for me.
```

# Acceptance Criteria

```
GIVEN I need to plan a trip at an affordable price.
WHEN I open the application,
THEN I am presented with the main page that includes feature trips and/or current deals.
WHEN I select a featured deal or trip,
THEN I am presented with the trip details and option to select dates of travel.
WHEN I select dates of travel,
THEN I am guided to select my choice from available rooms.
WHEN I select my room of choice,
THEN I am presented with a full view of my selections and the option to move forward or go back to make changes.
WHEN I click the option to go back,
THEN I am presented with the option to make changes to my selected choices.
WHEN I click continue,
THEN I am presented with the option to continue as a guest or create an account.
WHEN I click 'continue as guest',
THEN I am directed to pay for trip in full or at property if booking is hotel only.
WHEN I complete my transaction,
THEN I will get a confirmation number and email with full itinerary.
WHEN I submit card information and transaction is declined,
THEN I will get an alert and given the opportunity to resubmit card information.
WHEN I click 'create account',
THEN my choices are saved and I am directed to fill in my personal information.
WHEN I complete the sign up form,
THEN I can click 'done' and will be redirected back to checkout with logout option at the top of page.
WHEN I checkout,
THEN I will see the payment options, points earned for this transaction, and other offers.
WHEN I complete my transaction,
THEN I will get confirmation number and email with full itinerary.
WHEN I click 'logout',
THEN I am redirected to the main page.
WHEN I click 'login',
THEN I get a welcome back alert and top tabs to view profile, logout, and live agent.
WHEN I click the profile option,
THEN I am able to update account information, save payment methods securely, create travel Wishlist and favorites, and update or reset password.
WHEN I click 'live agent',
THEN I am able to chat with an agent to create my next adventure.
WHEN I click vacation packages,
THEN I am able to see special offers or package deals.
WHEN I am on the main page,
THEN I am able to search the location I want to travel to and book.
```

## Installation

GitHub Repo: https://github.com/brittanyb89/Travel-Agent-App

Deployment:
Heroku:
Netlify:

## Mock-Up

The following image shows the web application's appearance and functionality:

![Homepage](homepage.png)

![User page](login%20page.png)

## Usage

Click link in top right corner of page to add notes. Once your notes are added and saved, you will be able to view them on the side of the page along with other saved notes.

## License

![NPM](https://img.shields.io/npm/l/inquirer?style=plastic)

MIT License

Copyright (c) 2023 Brittany Burton, Anthony Dandino, John Robinson, and Joseph Stzembosz

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Badges

![NPM](https://img.shields.io/npm/l/inquirer?style=plastic) ![badmath](https://img.shields.io/github/languages/top/lernantino/badmath) ![npm collaborators](https://img.shields.io/npm/collaborators/inquirer) ![Dependents (via libraries.io)](https://img.shields.io/librariesio/dependents/npm/inquirer) [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

# MERN (Apollo GraphQL) Server Template

Monorepo for MERN (MongoDB, Express, React, Node) stack with Apollo GraphQL server. It uses Tailwind CSS for styling, which can be integrated with React component libraries such as MUI.

[Server](./server/README.md) | [Client](./client/README.md)

## Commits

To help ensure great commit messages for this project, consider using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary). Here's [an extension](https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits) to help you do that.

## Branching

`main` should only be for `Initial commit` and then not be used again until you are ready to deploy **something.** You should create a `dev` branch and use that for all development. Then, you can create feature branches off of `dev` and merge them back into `dev` when they are ready.

You could even do: `dev-server` and `dev-client` if you want to separate the two. From there, you might have: `dev-server-graphQL-type-defs` and `dev-server-graphQL-resolvers` and so on.

Delete branches after they are merged. You can always create a new branch if you need to. You should probably not have more than 3-4 branches at any 1️⃣ time. Use `git branch` to confirm.

### Protect ~~This 🏠~~ Your `main` Branch

Here's [a guide](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule) to do that.

It should be protected from force pushes and deletions. It should also require at least one review before merging.

## Code Quality

It might be good time to have [this](https://github.com/ryanmcdermott/clean-code-javascript) open and see how much of this you can apply.

## Getting Started

You probably want to work on `server` and `client` separately, and then you can start them together with `npm run dev` from the root for development.

## Questions❔

Ask sooner rather than later!
