files can contain context of what they are. For example, a photo can contain a label: photo of x.

a certifier's public key can be proven by a certification of a file such as a video where the certifier proclaims that it owns the public key.

a certifier can certify anything for the benefit of anyone. the certifier can include in the file a link to verify the certifier's ownership of the public key.

to prove the identity of the certifier of a string of text, one can show proof of the certifier's identity.

one can certify an offer to another. the offer can be a file that can contain proof of one's identity, e.g., a qr code link to one's credentials. the contract is complete by the acceptance of the other by returning the offer to the sender with a similar qr code for the returner's identity.

use this for elections. since there are many attributes to prove, the transaction shall contain a link to a JSON file that contains info to prove all the required credentials. call an election. add all details necessary, including timestamp, question, and choices. a choice will be represented by public key. hash all details. the memo will contain a readable url to a JSON file that contains the required verification details: election hash, credentials needed to vote + identituy.

to keep vital data semi private, get the certifier to designate a certain unique amount number to the complete vitals of the holder. so that to avoid duplicity, one need only look at the certifier, the amount, and the hash. Remove duplicate hashes.