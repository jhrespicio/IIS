files can contain context of what they are. For example, a photo can contain a label: photo of x.

a certifier's public key can be proven by a certification of a file such as a video where the certifier proclaims that it owns the public key.

a certifier can certify anything for the benefit of anyone. the certifier can include in the file a link to verify the certifier's ownership of the public key.

to prove the identity of the certifier of a string of text, one can show proof of the certifier's identity.

one can certify an offer to another. the offer can be a file that can contain proof of one's identity, e.g., a qr code link to one's credentials. the contract is complete by the acceptance of the other by returning the offer to the sender with a similar qr code for the returner's identity.

use this for elections. call an election. add details, including timestamp, question, choices, and election period. a choice will be corresponded with a public key. hash the details.

one will vote by sending to one's choice's public key. the memo will contain a readable url to a JSON file that contains the required verification details: the election hash, the credentials needed to vote, and those needed to prove identity (but only for purposes of avoiding duplicity).

to keep the identity creds from direct disclosure, get the certifier of vital creds to designate a unique number. he can use that number as the designation (amount of the payment) for the hash of all the vital data of someone. to avoid duplicity, one need only look at the vital hashes of the voters.

to prove a file, it is useful to have the file.

this implementation exposes the public key. the alternative is an implementation for anonymous voting. but the problem there is that it cannot be verified whether a vote is by a ghost.