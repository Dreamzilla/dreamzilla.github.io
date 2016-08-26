## I've generated a key with a passphrase, but the passphrase is not requested on connection

Serverauditor supports RSA, DSA, and ECDSA keys for passwordless login. And you may protect your private key using a passphrase. This means that the private key will be encrypted using a passphrase to add an aditional layer of security. Serverauditor **stores the passphrase** together with the key's other values in the keychain. Because of this the passphrase will not be requested on the establishment of a connection. 

In case you wish that the passprhase will be prompted, **simply remove the passphrase** from the  key's settings in the Key chain.
* Navigate to the specific key
* Remove the value if the `Passphrase` field

For detailed instructions [Android users click here](../android/faq/troubleshooting/passphrase.md) and [iOS users click here](../ios/faq/troubleshooting/passphrase.md).