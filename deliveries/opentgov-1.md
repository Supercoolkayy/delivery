# Milestone Delivery

**The delivery is according to the official [milestone delivery guidelines](https://github.com/w3f/Grants-Program/blob/master/docs/Support%20Docs/milestone-deliverables-guidelines.md).**

* **Application Document:** [Opentgov Application](https://github.com/PolkadotOpenSourceGrants/apply/blob/master/applications/opentgov.md)
* **Milestone Number:** 1

**Context**

Opentgov is a complete Telegram wrapper for Polkadot's decentralised treasury.

This first milestone provides a self-custodial Telegram bot that uses a governance proxy to vote on proposals submitted to the treasury.

It also comes with a web application and dedicated back end to track live voting proposals in a user-friendly way.

**Deliverables**

| Number | Deliverable | Link | Notes |
| ------------- | ------------- | ------------- |------------- |
| 0a. | License | [Core README](https://github.com/mar1/opentgov/blob/main/README.md#-license) | The entire app is licensed under MIT. |
| 0b. | Documentation | [Bot README](https://github.com/mar1/opentgov/blob/main/bot/README.md) | In addition to this guide, the entire code had been commented thoroughly. |
| 0d. | Repo | [Repository](https://github.com/mar1/opentgov/) | The 3 components (bot, website and backend) are available on GitHub. |
| 0e. | Article | [X Thread](https://x.com/opentgov/status/1926665183839027463) | An article had been published to explain how to use this project. |
| 0f. | Social Media | [X account](https://x.com/opentgov) [TG group](https://t.me/opentgov) | The X account and the Telegram group are now both operational |
| 1a. | Front-end | [Repository](https://github.com/mar1/opentgov/website/) [Website](https://opentgov.com) | The Opentgov website is now tracking proposals and update them every 15 minutes. |
| 1b. | Telegram Group | [Repository](https://github.com/mar1/opentgov/backend/) [TG Group](https://t.me/opentgov) | The Opentgov automated group is now operational and updated automatically. |
| 1c. | Bot | [Repository](https://github.com/mar1/opentgov/bot/) | The self-custodial Telegram voting bot is now fully available. |
| 1d. | Documentation | [Setup Guide](https://opentgov.com/setup-bot) | A dedicated page on the website is helping users to setup the bot. |

**Additional Information**

I was very happy to work on this milestone. I'm pretty proud of the result: the site and the bot both fulfil the functions I detailed in my application. I have also tried to make the code clean and easy to understand, with lots of comments explaining how it works.

However, I can see that there are still two key issues that need to be addressed to make this project accessible to the general public. Firstly, installing Node.js and its dependencies is still somewhat complicated, even with the guide. This should be easier with the CLI planned for milestone 2. Secondly, 20 DOTs are currently required to create a governance proxy. This is a significant barrier to entry, even if the user can recover them later. I believe that migrating the treasury to AH should solve this problem.

Finally, I would like to apologise to the curators for the delay in delivering this project. I originally planned to complete it in one month, but it ended up taking over two months. I will do my best to deliver the second milestone more quickly.
