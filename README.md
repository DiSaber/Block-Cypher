# Block Cypher
## Installation 
To install the program just download "Block Cypher.exe" from above or from [here](https://github.com/lolapus/Block-Cypher/raw/main/Block%20Cypher.exe). You can place it anywhere but you might consider placing it on your desktop or creating a shortcut for your own convinience. Once you have set your password you can share your public key with anyone and they can use it to generate an encrypted message that only you can decrypt.
## Best practices
First and foremost I highly suggest you write down your password in a secure location as there is no way to recover it. You should create a file titled "contacts" somewhere on your device and store the public keys of everyone so you only exchange keys once. If you want certain messages you recieve to be safe from deletion you may want to store the encrypted copy somewhere on your device.
## Resetting Password
Unfortunately there is no way to recover your password as AES 256 is irreversible. You can however delete the file titled "BlockCypherKeys.dat" at the directory "C:\Users\\{Username}\AppData\Roaming" to reset the application.
## Technical specifications
I use 8192 bit RSA encryption for the message sharing and AES 256 to securly store the private keys.
