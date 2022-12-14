# stream-page

This repo, *stream-page*, has the React site with components for connecting a wallet and minting tokens.
Check out the other repo, *stream-token*, for the smart contract code and hardhat tasks.

Site deploys automatically to [Amplify](https://main.d2l5p8khnlyxk6.amplifyapp.com/).

```
on github.com website, make a completely blank new repo
github will show commands you'll use below

$ npx create-react-app stream-page
$ cd stream-page
$ git remote add origin git@github.com:AraBlocks/stream-page.git
$ git branch -M main
$ git push -u origin main

$ npm start (build and host locally)
$ npm run build (build locally to static)
$ git push (and amplify builds and hosts the new site)
```
