## NIP-09 deletion 

  In reference to https://github.com/nostr-protocol/nips/blob/master/09.md

  ## Design considerations & best practices
  1. There is no guarantee of deletion on nostr. Therefore it is misleading for nostr apps to refer a request to delete as a "delete".
  2. Superior terminology of "retract" sets expectations accordingly.

  ## Open & unanswered design questions
  1. Should the app team warn the user that there is no guarantee anything can be deleted, once posted to nostr?
  2. If yes, when is the right moment for this? For instance, is it prior the user's first nostr post? 


