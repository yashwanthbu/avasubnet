# Avalanche Advance 

This project provides an overview about the creation of subnet , deploying it locally in WSL and interacting with it .

## Description

In our project, I have created a subnet called 'subnet' and chain id-'1233' with token symbol as 'YBU' . After deploying this subnet locally, we are able to interact with it using remix IDE where we deploy our game contract which has many functions like mint, burn, transfer, allowance, approve and stacksof100 function to the subnet by changing the environment to 'injected provider'and interacting with it.

## Getting Started

### Executing program

You need to copy and paste this code(sub.sol) in remix in order to deploy your contract to the subnet.

Then, open your terminal to setup your subnet.

Install the Avalanche CLI and export the path before you run the below commands:

```shell
avalanche subnet create subnet
```
```shell
avalanche subnet deploy subnet
```
The subnet gets deployed locally where RPC URL, chain ID, Symbol and private key will be provided 

This configuration is applied to the metamask to connect to the subnet deployed.

Then, you can enter the private key to import the account with test tokens(10000)

After this, you can change the environment to injected provider and connect your metamask to deploy your contract to the subnet created.

## Authors

Yashwanth BU
[@yashwanthbuu@gmail.com]


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
