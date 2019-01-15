<h1 align="center">
  <br/>
  <img src=".github/aragonpm.png" alt="APM">
  <br/>
  APM Hackathon
  <br/>
</h1>

<h4 align="center">Welcome to the first APM Hackathon</h4>

<p align="center">
  <a href="#what-is-apm">What is APM?</a> •
  <a href="#what-is-this-hackathon-about">What is this hackathon about?</a> •
  <a href="#process">Process</a> •
  <a href="#thanks">Thanks</a>
</p>



# What is APM?

**APM** stands for **Aragon Package Manager**. It is a decentralized package manager designed to handle the upgradeability of smart contracts as well as arbitrary data blobs. The best way to learn about APM is to read this [article](http://blog.aragon.one/using-apm-to-replace-npm-and-other-centralized-package-managers/) and browse the [doc](https://hack.aragon.org/docs/apm.html).

# What is this hackathon about?

Most of us rely on NPM for everything we work on. NPM is far from being perfect, though: centralized infrastructure, security issues, lack of incentivization, etc.

The goal of this hackathon is to spawn a series of initiatives to enhance APM to the point where it become a serious - and backward compatible - alternative to NPM. As a first step toward this goal this hackathon will focus on two topics.

## T0 - APM User Interface

All APM registries and repositories related data are stored either on-chain or over IPFS. That's great for decentralization but not so great for the end user experience. The goal of this topic is to develop end-users interfaces allowing to search through APM registries and browse packages versions. Let's build the [npmjs.com](https://npmjs.com) of APM!

### Ressources

- [Aragon Design Guideline](https://wiki.aragon.org/design/). In case you need some inspirations regarding your design.
- [GraphProtocol Aragon Subgraph](https://github.com/graphprotocol/aragon-subgraph). TheGraph allows you to index and search through Ethereum events and IPFS data. It may (or may not) be a good starting point to offer decentralized searchability to APM registries.

## T1 - NPM backend

For now, everyone uses NPM, right? So what if could we create an NPM backend serving APM-hosted packages? The goal of this topic is to develop an enhanced version of [APM serve](https://github.com/aragon/apm-serve) complying to the [NPM Registry API](https://github.com/npm/registry/blob/master/docs/REGISTRY-API.md).


### Resources

- [APM serve](https://github.com/aragon/apm-serve). A Web 2.0 server for Web 3.0 APM hosted dApps and packages.
- [NPM Registry API](https://github.com/npm/registry/blob/master/docs/REGISTRY-API.md). The API any NPM registry must comply to.


# Process

This hackathon will _start remotely on January, 20th 2019 and end up on site January, 30th 2019_ - on the last day of [Aracon](https://aracon.one). It is thus aimed at _people actually attending Aracon_ (even though it starts a week before for practical reasons).

## Submission Guidelines

Here’s how it works.

### 1. Come and chat

The best way to get started is to come and chat on the `#hackathon` channel of [Aragon's chat](https://aragon.chat/channel/apm-hackathon). Ask any question you have to the team, discuss the ideas you wanna hack on with the community, coordinate to gather as a team, etc.

### 2. Create an issue

Once you know what you wanna work on - and with who you wanna work on - open a new issue in this repository. We have created a couple of issue templates so it should be pretty straightforward: just choose the `Topic 0 - UI` or `Topic 1 - NPM` template (depending on what you wanna work on) and draft a quick summary of the idea you wanna work on. Use this issue to coordinate with other participants, request for help / teammates, etc. We also added a convenient `request for hackers` label. Feel free to use if you're looking for teammates and check the other issues to see if there are other teams there looking for people to work with.

### 3. Buidl!

That's when it comes to stop sleeping and start buidling. Use the issue you created in step 2 to let others know where your project lives. And remember that whatever you are working on, your project should include an **Open Source License** of [some form](https://opensource.org/licenses), and be accessible to everyone after the submission deadline.

### 4. Gather at Aracon

We will have a entire room dedicated to this hackathon on the first day of [Aracon](https://aracon.one): January, 30th 2019. That's why we require that _at least one person per team actually attend Aracon to 'represent' its team there_. Come here and gather with your team: use that f2f day to polish your project and make it ready for submission.

### 5. Fork and PR

Once you're ready, fork this repository, add a markdown file following [this template](https://github.com/AragonDAC/APMHackathon/blob/master/submissions/exampleProject.md) inside the `submissions` folder, and open a PR. These PRs must be opened before **January 30, 00:00 CET** to leave our jury enough time to review everyone's code. *Opening a Pull Request establishes your project as an "official" submission.*

### 5. Enjoy the rest of Aracon

You can now breeze and go back to an (almost) normal life. Enjoy the wonderful [talks / panels](https://aracon.one/agenda) of Aracon and wait for the winners to be announced!

## Dates

**January, 20th.** Registration begins.

**January, 30th.** Submission deadline.

**January, 31th.** Winners Announced.


## Scoring

Submissions will be graded across the following equally-weighted criteria:

1. Functionality
2. Creativity
3. Difficulty
4. Design

## Prizes per topic

**Winners.** 1000 ANT ???

**Runners up.** ???

# Thanks

This README is a pale copy of the [Colony Hackathon's one](https://github.com/JoinColony/colonyHackathon). Thanks folks!
