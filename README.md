ringmail
========

It is clear that there is no easy system that will make email secure.
I am proposing to create a system which will not need servers and be 100% secure.
Something based on the bittorrent-like network allowing everyone to be their own host.
But if they are offline have the network help by holding it in shards and then allowing only that client to download it.
Similar to bittorrent torrent system itself.

1. The sender will send the message encrypted.
2. It will be broken up into pieces and sent to peers.
3. The peers will only know to hold these pieces.
4. The client of the reciever comes online.
5. The client retrieves any pieces waiting to be sent and all peers holding those pieces will erase the pieces so the mail can only be retrieved once.

Limit the Mail system to 102.4 mb allowing a lot of text but not much room for sending videos or images.
