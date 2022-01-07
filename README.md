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

1. Fork this repository on Github
2. Clone your forked repository (not our original one) to your hard drive with `git clone https://github.com/{username}/cronos-docs.git`
3. `cd cronos-awesome`
4. Make a copy of `MAKE_COPY.json`, rename the copy and start filling out the fields.

### Fields 
1. name: `The official name of your project`
2. category: `Select from categories below`
3. status: `The official name of your project`
4. origination: `The official name of your project`
5. description: `The official name of your project`
6. logo: `The official name of your project`
7. link: `The official name of your project`
8. twitter: `The official name of your project`

Note: If your project belongs to more than one category, you can add each secondary category as a comma separated entry. (e.g. Defi, Nft etc.)
### Categories
`Bridge`,
`DEX`,
`Farm`,
`Gaming`,
`Infrastructure`,
`Launchpad`,
`Lending`,
`News`,
`NFT`,
`Optimiser`,
`Options`,
`Others`,
`Reserve`,
`Stablecoin`,
`Tools`,
`Wallet`,

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

Once review and approved, you should see your projects on [crypto-org-chain/cronos-awesome/tree/staging](crypto-org-chain/cronos-awesome/tree/staging).
