# offlineLiskTools
- Tools for offline creating and signing type 0 and type 3 Lisk transactions. 
- Tool for online sending the offline created transactions.

Just download and extract the .rar files. Since the tools are just html site with some javascript code, you should be able to run it on multiple platforms. I tested it on Windows and Linux Ubuntu.

# offlineCreateStdTransaction:
- this should be used on an offline pc which is not connected to the internet
- copy or type your passphrase into the first input box
- copy or type your second passphrase into the second input box (or leave blank if you don't have one)
- type in the amount of LSK you want to send. Or use the arrow at the right hand side of the third input box
- copy or type the recipient adress into the fourth input box
- click the blue "Generate transaction" button
- The signed transaction will be display as a string and as QR-Code
- follow the instructions below for: onlineSendTransaction

# offlineCreateSecondSecretTransaction:
- this should be used on an offline pc which is not connected to the internet
- copy or type your passphrase into the first input box
- copy or type your DESIRED second passphrase into the second input box
- click the blue "Generate transaction" button
- The signed transaction will be display as a string and as QR-Code
- follow the instructions below for: onlineSendTransaction

# offlineCreateSignedVotingTransaction:
- this should be used on an offline pc which is not connected to the internet
- copy or type your passphrase into the first input box
- copy or type your second passphrase into the second input box (or leave blank if you don't have one)
- copy an array with public Keys of the delegates that you want to vote (or unvote) into the third input box
  - You can also use the arrays that I have added to this project (VotingArrays.txt)
   - If you use the VotingArray.txt you can also send me an Email to lisksnake@gmx.de and 
     I will inform you when voting needs to be changed (i.e. one delegate not forging any more,......)
- click the blue "Generate transaction" button
- The transaction will be display as a string and as one or two QR-Codes
  - for 33 delegates the QR-Code is too complex and a standard web cam is not able to decode it.
  - So i split the transaction information into 2 QR-Codes
  - Please remenber that when you use the online tool. You have to scan twice!!
- follow the instructions below for: onlineSendTransaction
