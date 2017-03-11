# InsuranceDApp

The future of Health Care

# The Purpose

This is a Decentralized App based on Ethereum blockchain aiming to solve some tricky issue in the Health Care industry.
We mainly provide a solution preventing :
- Doctors from frauding the Social Security service or Insurance companies by asking for multiple refunds for one unique service
- Insurance companies increasing the insurance policy price for people getting health trouble and who need more traitements.


# Smart Contracts
Please see folder ``contracts``, you will find all the smartcontracts and their behavior.

#  Installation
1. install testrpc which is a Node.js based Ethereum client for testing and development. It uses ethereumjs to simulate full client behavior and make developing Ethereum applications much faster. It also includes all popular RPC functions and features (like events) and can be run deterministically      to make development a breeze. and run
    ```
    $ npm install -g @angular/cli
    $ npm install -g ethereumjs-testrpc
    $ npm install -g truffle
    ```

2. start using the app with
    ```
    $ npm install 
    $ npm run startd
    $ testrpc
    ```
after this open a new terminal and run the commands bellow to deploy the smart contracts via testrpc to the local node.
    ```
    $ truffle build
    $ truffle metigate
    ```

3. You can also test th contract
    ```
    truffle test
    ```

# Underdevelopment
The project have been developed during a Hackathon, so it's not to be put in production right now.
