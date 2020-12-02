files can contain context of what they are. For example, a photo can contain a label: photo of x.

a certifier's public key can be proven by a certification of a file such as a video where the certifier proclaims that it owns the public key.

a certifier can certify anything for the benefit of anyone. the certifier can include in the file a link to verify the certifier's ownership of the public key.

to prove the identity of the certifier of a string of text, one can show proof of the certifier's identity.

use for contracts. e.g., one sends (certifies) the contract file to the other parties. the contract contains qr codes to all the parties' ID proof. stamp "offer till returned" on the contract. the contract binds the party who, with respect to a sending party, sends the same file back to him. the sending back is the acceptance of the offer.

use this for elections. call an election. add details, including timestamp, question, choices, and voting period. assign a unique public key to each choice. hash the details.

one will vote by sending to one's choice's public key. the memo will contain a readable url to a JSON file that contains the required verification details: the election hash, the credentials needed to vote, and those needed to prove identity (for purposes of avoiding duplicity).

to keep the identity creds from direct disclosure, get the certifier of vital creds to designate a unique number. he uses that number as the label (amount of the payment operation in the transaction) for the hash of all the vital data of the recipient. to check for duplicity, one need only look at the vital hashes of the voters.

exclude votes outside the voting period and before the call.

to prove a file, it is useful to have the file.

this implementation exposes the public key. the alternative is an implementation for anonymous voting. but the problem there is that it cannot be verified whether a vote is by a ghost.