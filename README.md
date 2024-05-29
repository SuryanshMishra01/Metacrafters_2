# Metacrafters_2
This solidity program "myToken" is a simple program which imitates the token creation (minting and burning coins) process on my local Blockchain

# Description
The program consists of: 
1) 3 public state variables which will provide the token name, token abbreviation and total supply for my token.
2) Minting function "mintToke()" which will take address and value as parameters and then it increases the total supply by that number and increases the balance of the address by that amount.
3) Burn function "burnToken()" which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
4) This burn function will also check the amount to be burned must be less than or equal to the balance present in that address

# Getting Started
## Executing Program 
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.
Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the "myToken" file in my repo with a .sol extension. Now compile and deploy the program. All done !! 

## Interacting with Program
![image](https://github.com/SuryanshMishra01/Metacrafters_2/assets/116947777/47021f4c-86ac-41d4-999c-cc9fa6c7d195)

After deployment, we can interact with program by calling the functions that will appear on the left as shown in the screen shot.

# Author
Suryansh Mishra
@suryanshmishra0704@gmail.com

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
