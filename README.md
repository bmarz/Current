# Current
A distributed social networking protocol

This project is for creating a distributed social networking protocol that can be implimented by anyone who would desire to make a client for it.

The name "Current" is very relivant, as a distributed system, in order to be practical across multiple platforms must be limited in the amount of information it can store. Thus the purpose of "Current" is not to be a repository but a rolling stream, or 'current' of the latest events. And since it could only store the latest events along with a small history, it is allways 'current', hence it's name. The feeds, or pages would also, of course, be called 'currents'.

The requirements for Curreent are as follows:

1. Be completely distributed with no need for a dedicated server, ever.
  a. Utilize a limited amount of space, no more than 1 or 2 GB.
  b. Maintain up-to-date 'currents' the user is subscribed to reguardless of movement between networks.
  c. A block chain of some variety is probably the best option
2. Allow the creation of 'currents' that are either private or public.
3. The creator of the 'current must be able to control the nature of the current
  a. Public currents must not be able to be 
