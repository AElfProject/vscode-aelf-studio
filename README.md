# aelf-studio

**aelf-studio** is a comprehensive Visual Studio Code extension designed to streamline the development, testing, and deployment of smart contracts on the AElf blockchain. This tool empowers developers to efficiently manage the entire lifecycle of their smart contracts within the VS Code environment, offering powerful features like AI auditing, deployment management, and transaction tracking.

## Key Features

- **Build Smart Contracts:** Compile your aelf smart contracts directly within VS Code using simple terminal commands.
- **Test Smart Contracts:** Run tests and validate the functionality of your smart contracts before deployment.
- **Get Testnet Tokens:** Easily claim testnet tokens for testing your contracts without leaving your development environment.
- **Deploy Smart Contracts:** Deploy your contracts to the aelf testnet or mainnet with a few clicks.
- **Check Transaction Status:** Track the status of contract deployment and other blockchain transactions directly from the extension.
- **AI Audits:** Leverage built-in AI tools to audit your smart contracts for vulnerabilities and potential issues before deployment.
- **Deploy from Local:** Deploy your locally built smart contracts directly to the aelf blockchain.

---

## How to Install

1. Open Visual Studio Code.
2. Click the Extensions icon on the left.
3. Search for "aelf-studio" in the search bar.
4. Select the aelf-studio extension and click Install.
5. If prompted, reload VS Code to finalize the installation.

---

## Getting Started

1. **Create a New Project:**

- Open the terminal in VS Code.
- Run `mkdir my-contract` to create a new directory.
- Open the folder with `code my-contract`.


2. **Generate a Smart Contract:**

- In the terminal, run `dotnet new aelf -n MyContract`.
- This command will create a basic aelf smart contract template.


3. Build the Contract:

- Navigate to the project folder by typing `cd src`.
- Run `dotnet build` to compile your contract.


4. **Test the Contract:**

- Run your contract tests within VS Code to ensure everything is functioning as expected.


5. Get Testnet Tokens:

- Click the aelf icon in the bottom right corner.
- Choose **Get Testnet Tokens** and follow the instructions to receive tokens for testing.


6. **Deploy the Contract:**

- Use **Deploy from Local** by selecting the aelf icon.
- Follow the prompts to deploy your smart contract to the aelf testnet or mainnet.


7. **Check Transaction Status:**

- After deploying, you can check the status of your transaction directly from the extension. This ensures you know when your contract is successfully deployed.


8. **AI Audits:**

- Before deploying, use the **AI Audits** feature to scan your contract for any security issues or potential vulnerabilities.

---

## FAQ

**1. What tools do I need to use this extension?**
You’ll need to have VS Code and the .NET SDK installed to create and build aelf smart contracts. You can download .NET [here](https://code.visualstudio.com).

**2. How can I get testnet tokens for free?**
Click on the aelf icon in the bottom right corner of VS Code and choose Get Testnet Tokens. Follow the instructions to receive tokens for testing purposes.

**3. What is AI Auditing, and why is it important?**
The AI Auditing feature scans your smart contracts for security vulnerabilities and potential issues, helping you ensure that your contracts are secure before deploying them to the blockchain.

---

## Support

For issues or questions, please visit our [GitHub repository](https://github.com/AElfProject/vscode-aelf-studio) or raise a ticket in the issues section.

