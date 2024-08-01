#Building Your Own Empire Of DeFi
In the following project you are going to learn how to set up your own EVM Subnet on Avalanche, which is indeed a great initial step for building the kingdom of DeFi.

#Description
In the document you will find a detailed procedure and explanation on how to create your own Subnet and Deploy it using the Avalanche CLI, which is also customizable. You then connect this subnet to your MetaMask wallet by giving the right RPC URl and the other details. Hence having the subnet created you can now use it to deploy two smart contracts on remix and also interact with it. Note that in some network cases, the Avalanche CLI doesn't get installed properly as the network provider might have blocked it. The alternative is to access and run your code on remix u may use this link to open Remix : https://remix.ethereum.org/.

#To Begin With
To get started initially, the Avalanche CLI has to be installed on to your local system on linux(u can also install and run it using Ubuntu) , you may also use this link for installation: https://docs.avax.network/tooling/cli-guides/install-avalanche-cli based on your convenience . Once installed by fulfilling the following guidelines in the website, you will have to create your own subnet. This can be done by executing the following commands on your terminal:

```avalanche subnet create mySubnet```

```avalanche subnet deploy mySubnet```

To create and deploy the subnet on the avalanche CLI, the above mentioned commands can be utilised.

#Output Process
Once you're done with the creation and deploying part of the Subnet, you will be provided with the details of your subnet on the terminal. You can use these details and then create a new network on the metamask wallet which can be used for operating on your subnet.
You may then copy and paste the code provided. And then deploy it on remix. Remember that it should be deployed on the Injected provided(metamask) server. Now you can connect your metamask wallet to remix and run any number of functions on the remix application and interact with your subnet.

##Author

S.Chaitanya Sai

e-mail: chaitanya.sai3539@gmail.com

#License

This smart contract is licensed under the [MIT License].
