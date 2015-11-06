* note whether its a library, stand-alone client/server, or both
* mention SSH v1 support (I guess not supporting it could be counted as a 
  feature these days... or at least it is important that one can disable it)
* In the comparison tables, display how many impls per proto / protos per implicit=false
  there are.

* Distinguish clients and servers in comparison; perhaps offer
  separate comparison pages for clients, servers, and combined...?



Add more text on the front page: What the purpose of this site is,
and what is not.

E.g. a list of supported combos is meant to help decide which
protocols you can safely en/disable without breaking support
for certain clients.

It should NOT be used as exclusive source for deciding which SSH
implementations to use, as just supporting a protocol does not 
mean the support is correct, bug free, secure, etc.


BLA BLA


ALso allow comparing a subset (2? maybe a few more) of implementations,
so that one can directly see which protocols are shared by some clients.
I.e.: for two implementations, list only the protocols they have in common
(For comparing more than two, we'll have to leave the static-only design of the site, though)


* add more impls:
  * everything on https://en.wikipedia.org/wiki/Comparison_of_SSH_servers
  * everything on https://en.wikipedia.org/wiki/Comparison_of_SSH_clients
  * Chilkat http://www.chilkatsoft.com/ssh-features.asp
  
    diffie-hellman-group-exchange-sha256,diffie-hellman-group-exchange-sha1,diffie-hellman-group1-sha1,diffie-hellman-group14-sha1,curve25519-sha256@libssh.org,ecdh-sha2-nistp256,ecdh-sha2-nistp384,ecdh-sha2-nistp521
    ssh-rsa,ssh-dss
    ssh-dss,ssh-rsa
    wodFTPD 2.1.4
    aes128-cbc,twofish128-cbc,blowfish-cbc,3des-cbc,arcfour128,arcfour256
    aes256-ctr,aes128-ctr,aes256-cbc,aes128-cbc,twofish256-cbc,twofish128-cbc,blowfish-cbc,3des-cbc,arcfour128,arcfour256
    aes256-cbc,aes128-cbc,twofish256-cbc,twofish128-cbc,blowfish-cbc,3des-cbc,arcfour128,arcfour256
    hmac-sha2-256,hmac-sha1,hmac-sha2-512,hmac-md5,hmac-ripemd160,none
    zlib,zlib@openssh.com,none

    secp256r1
    secp384r1
    secp521r1