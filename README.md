# Project Title

This full-stack application facilitates token deposit, withdrawal, owner verification, and ownership transfer functionalities.

## Description

This contract features four main functions. The first function allows users to deposit funds into the contract securely. The second function permits only the contract's owner to withdraw funds. The third function verifies whether a specified address is the current owner. Lastly, the contract includes a function for transferring ownership between addresses, which can only be executed by the current owner. These functionalities ensure secure management of funds and ownership within the contract.

## Getting Started

### Installing

- Clone the Repository

### Executing program

After cloning the github, you have to run the following command

1. Inside the project directory, in the terminal type:

```sh
npm i
```

2. Open two additional terminals in your VS code
3. In the second terminal type:

```sh
npx hardhat node
```

4. In the third terminal, type:

```sh
npx hardhat run --network localhost scripts/deploy.js
```

5. Back in the first terminal, launch the front-end.

```sh
npm run dev
```

## Help

In case any problem or error occurs, make sure you have correct Solidity version and along with the directory. Check on the parameters.

```sh
For additional help, you can even refer Remix documentation or Solidity documentation
```

## Authors

Contributors names and contact info

Name: Akash Kumar Sinha <br>
Contact info: akashkumarsinha529@gmail.com

## License

This project is licensed under the MIT License. Check out the License.txt for details
