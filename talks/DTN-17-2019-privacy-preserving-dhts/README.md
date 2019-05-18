## Talk summary

**Abstract**: Naive P2P network implementations make it easy and cheap for many parties to
collect data about user behaviour. In this talk we motivate the importance of
privacy and security in P2P networks, show privacy vulnerabilities of
Distributed Hash Tables and outline mechanisms that can be used by developers
to enhance privacy of P2P applications.

---

Distributed Hash Tables (DHT) are an important primitive which allow multiple
nodes to collaboratively store and retrieve data in a completely decentralised
networks. Thousands of users are using projects and service which rely
on DHTs: Bittorrent, IPFS, Freenet, Ethereum are just examples of projects
leveraging DHTs to store and retrieve data in decentralised networks. With the
upcoming Web 3.0 and the increasing popularization of P2P networks, it is only 
expected that DHTs will become even more important in future connected
applications.

The most popular DHT vanilla protocols leak information about which users are
storing and retrieving what files, making it easy for adversaries to gather data
that can be correlated to understand what network users are up to, their 
interests and behaviour patterns. The data leaked can be used by adversaries 
for mass surveillance, censorship and privacy attacks on DHT users.

In this talk, we first dive into what are DHTs, how they work and how is user
activity data leaked. We discuss an hypothetical future in which P2P networks
are mainstream to understand how easy it is to perform privacy attacks that
disclose 

We go through some techniques and protocols to enhance privacy in DHTs
based on current research and applications such as onion routing, plausible
deniability protocols, friend-to-friend routing, oblivious transfer and the
Octopus DHT lookup protocol.

Finally `p3lib` is introduced as a toolbox of privacy enhancing primitives that
can be used by system developers to improve privacy of P2P systems and which is
fully compatible with [libp2p](https://github.com/libp2p). It is plug an play
privacy :)

### Additional Resources

[p3lib](https://github.com/hashmatter/p3lib) privacy preserving primitives and protocols (p3) for routing and messaging in P2P networks

[Privacy preserving networks notes](https://github.com/gpestana/notes/issues) [Privacy preserving networks notes -- DHT](https://github.com/gpestana/notes/issues/8)

[Research on P2P security and privacy](https://github.com/gpestana/p2psec)

