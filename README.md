# internship-mael

## 01.06.2021 
### Contributor assistant (CA)
1. [Project structure suggestion](https://github.com/cla-assistant/contributor-assistant/issues/14)

### CLA Classic
1. Setup a local instance of https://github.com/cla-assistant/cla-assistant  
2. Existing Features
    - Comments on each opened pull request to ask the contributor to sign the CLA
    - Allows contributors to sign a CLA from within a pull request
    - Authenticates the signee with their GitHub account
    - Updates the status of a pull request when the contributor agrees to the CLA
    - Automatically asks users to re-sign the CLA for each new pull request in the event the associated Gist & CLA has changed
    - Request more information from the CLA signer (custom fields)
    - Allow bot user contributions (allowlist)

### CLA lite
1. Existing Features
    - decentralized data storage
    - fully integrated within github environment
    - no User Interface is required
    - contributors can sign the CLA or DCO by just posting a Pull Request comment
    - signatures will be stored in a file inside the repository or in a remote repository
    - signatures can also be stored inside a private repository
    - versioning of signatures

#### Meeting recap
 - (CA) Keep `/src` folder but carry on with the modular approach
 - Review CLA classic PRs, run a local instance

## 02.06.2021
### Models & references
 - https://github.com/cla-assistant/cla-assistant-thesis
 - https://github.com/marketplace/actions/deploy-to-github-pages
 - https://opensource.com/article/18/3/cla-vs-dco-whats-difference
 - https://probot.github.io/apps/dco/

#### Meeting recap
 - Successfully ran a local instance of the CLA Assistant
   - Hint: add https on callback URL
 - Started the review of https://github.com/cla-assistant/cla-assistant/pull/688
 - Chat bot IA => FAQ

#### Ideas (CA)
  - If explicitely enabled, deploy a github-pages interface to manage the CA
  - Would be a modular website: there would be tabs for each enabled feature of the CA
  - When something is updated, just rebuild the part that's needed
