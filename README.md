<br />
<p align="center">
  <img src="./docs/assets/cronos.svg" alt="Cronos Logo" width="300">
</p>
<br />

# Cronos Ecosystem Project Template

The documentation in this repository site provides the template and specifications details to submit ecosystem projects to be included on the Cronos ecosystem page.

## Getting Started

### Prerequisites

You're going to need:

[gh-cli](https://cli.github.com/)

### Getting Set Up

1. Create a new file under `/projects`. GitHub will automatically fork the repo for you.
2. Then you can submit the file. This should create a new PR for you to submit to our `main` branch.


### Fields 
1. name: `The official name of your project`
2. category: `Select up to 3 items from Categories below`
3. logo: `Url to your logo`
4. description: `Brief Project Description`
5. link: `Url to your website`
6. twitter: `Url to your Twitter`

Note: If your project belongs to more than one category, you can add each secondary category as a comma separated entry. (e.g. `["Farm", "NFT"]` etc.)

### Categories (Select up to 3 categories)
`Bridge`,
`DEX`,
`Farm`,
`Gaming`,
`Infrastructure`,
`Launchpad`,
`Lending`,
`Metaverse`,
`News`,
`NFT`,
`Options`,
`Others`,
`Reserve Currency`,
`Stablecoin`,
`Structured Finance`,
`Tools`,
`Wallet`,
`Web3`,
`Yield Optimiser`,

### Commit Changes
```bash
git add .
git commit -m "commit comment"
git push -u origin main 
```
Note: Please make sure, you push to your forked repository

### Create Pull Request
if not Authenticated yet please run:

```bash
gh auth login
```
If the git CLI prompts the following: 

`Which should be the base repository (used for e.g. querying issues) for this directory`

Select the following base repository:

`crypto-org-chain/cronos-awesome`

Then:

```bash
gh pr create --base staging --head ${username}:main
```
This will programatically create PR based on your commit. Once we receive the PR we will review the project details and format.

Note: We only accept PRs to our `staging` branch.

Once review and approved, you should see your projects on [crypto-org-chain/cronos-awesome/tree/staging](https://github.com/crypto-org-chain/cronos-awesome/tree/staging).
