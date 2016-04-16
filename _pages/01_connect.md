---
layout: page
title: Connect
permalink: /connect/
---
You can connect to xmpp.dk using your favourite Jabber client. There's a long list of clients available over at [xmpp.org][jabber-clients]. 

## To create a @xmpp.dk account
Registration is handled in-band by your Jabber/XMPP client. This is the only way to create an account on xmpp.dk.  
  
Simply add _username_@xmpp.dk in your client and click “register” or check the box to “create this account on the server” to sign up.

## Connection Information

### Server

* Internet: xmpp.dk
* Tor: mjfjbs3547exsy6r.onion

### Security

* Require SSL/TLS
* When connecting to the hidden service you will get a warning about the TLS certificate not matching the host name. This is OK.

## Secure Communication
The connection between your client and xmpp.net is encrypted using TLS. The server prefers secure connections to other servers, however this cannot be guaranteed. 
Since you can't (and shouldn't) trust your xmpp server, I recommend you always enable [Off-The-Record (OTR)][off-the-record] in your chat client. This will give you end-to-end encrypted chat that cannot be decrypted while in transit
and, depending on the settings of your client, will not be logged on your local machine. 

## Federation
xmpp.dk allows federated connections to all other S2S TLS-enabled Jabber servers so you can chat with anyone that has a Jabber account. Note that Google Talk (has this been deprecated yet?) doesn’t support S2S connections.

## xmpp.net score
[![xmpp.net_score](https://xmpp.net/badge.php?domain=xmpp.dk)][xmpp.net]

[jabber-clients]: https://xmpp.org/software/clients.html
[off-the-record]: https://otr.cypherpunks.ca/
[xmpp.net]: https://xmpp.net/result.php?domain=xmpp.dk&type=client