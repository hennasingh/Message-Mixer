# Message-

### Problem Statement

Message Mixer Inc. offers a message-encryption service that transforms input text, using various ciphers, and displays the encrypted message to the console.

There are three encryption methods provided by this service:

A “Caesar Cipher” in which the characters of the input message are shifted alphabetically by a given amount.
A “Symbol Cipher” in which select characters from the input message are replaced with visually similar symbols.
A “Reverse Cipher” in which each word of the input message is reversed in place.

Following command can be run to test the code

```
node message-mixer.js ['caesar'|'symbol'|'reverse'] [amount]
```

### Sample examples

```
$ node message-mixer.js caesar 4
Enter the message you would like to encrypt...
> hello world
 
Here is your encrypted message:
> lipps asvph
 
$ node message-mixer.js 'reverse'
Enter the message you would like to encrypt...
> hello world
 
Here is your encrypted message:
> olleh dlrow
```

### Super-Encoder

The code in this file can be run in the following way

```
node super-encoder.js encode

node super-encoder.js decode
```
