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

#### Meeting summary
 - (CA) Keep `/src` folder but carry on with the modular approach
 - Review CLA classic PRs, run a local instance
