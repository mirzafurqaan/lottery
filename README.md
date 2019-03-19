//lottery.sol
At Remix IDE,
1.	Create a new Remix file lottery.sol in remix IDE http://remix.ethereum.org/ 
2.	Write the contract for lottery. 
3.	Make sure that the version you have written in solidity file and version in compile tab is same, else error will be generated.
4.	After compilation, deploy the contract in the run tab,
a.	Select environment- injected web3
b.	Select account – select any account from metamask, first account will be considered as manager account. You can change account and enter the amount in the lottery.
c.	Gas limit- it will default, no change in this field.
d.	Value- here you have to add amount which you want to enter in the lottery. The currency has to be selected as ether.
At Visual Studio Code,
1.	Open the Visual studio Code Editor
2.	Create a folder named lottery.
3.	Open PowerShell go to the directory lottery and enter the command-  git clone https://github.com/mirzafurqaan/lottery.git 
4.	In PowerShell, enter the command – npm install node-modules.
5.	In VS code, Open the lottery.js file from the src folder, and from Remix IDE, copy ABI(Application Binary Interface) paste it in the file.
6.	In PowerShell, run the command – npm start ,  it will start the server.
7.	Open the browser, run - http://localhost:3000/  , it will open the lottery page.
