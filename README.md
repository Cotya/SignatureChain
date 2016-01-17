Cotya/SignatureChain
====================

this is a signed Chain(aka github repositories with signed commits).  
It contains a lot of signatures for Composer packages.
First a simple sha256 signature, additionally a gpg signature.
The type of the second signature is free of choice.





## availabel tools to interact with this Chain

* https://github.com/Cotya/SignatureChainer




## why this is secure

warning: I have no Idea about how secure this is, I just trust existing
software to do the job properly.

Git is used by a lot of people and should make sure,
that changing the history does not happen without someone to notice.

gpg signing of commits should also make sure, everybody can
validate who added the signatures. They also give you the choice
to decide yourself who to trust.
