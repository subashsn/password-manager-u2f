# password-manager-u2f

  This is my attempt to build a password manager that I believe will protect my credentials better using U2F. 

  Universal 2nd Factor (U2F) is an open authentication standard that strengthens and simplifies two-factor authentication using specialized USB or NFC devices based on similar security technology found in smart cards.

  The goal is build a password manager that does not reveal all the credentials even when the client device is compromised. Right now if an attacker compromises the client device, the attacker will be able to obtain all the stored credentials once the master password is entered. Some providers use an U2F device, but only once for logging into the vault.

  Right now one of the major improvements I have thought of is to have the server send encrypted-passowrds individually by verifying a U2F device each time. Granted this increases the hassle, but provides significant security advantage. This way even if the attacker has full access on the victims device, he/she can obtain only one password at a time.

More info soon.
