# Current
> A distributed social networking protocol

This project is for creating a distributed social networking protocol that can be implimented by anyone who would desire to make a client for it.

The name "Current" is very relivant, as a distributed system, in order to be practical across multiple platforms must be limited in the amount of information it can store. Thus the purpose of "Current" is not to be a repository but a rolling stream, or 'current' of the latest events. And since it could only store the latest events along with a small history, it is allways 'current', hence it's name. The feeds, or pages would also, of course, be called 'currents'.

The requirements for Curreent are as follows:

1. Be completely distributed with no need for a dedicated server, ever.

  a. Utilize a limited amount of space, no more than 1 or 2 GB of cache per device - NOT per current.
  
  b. Maintain up-to-date currents the user is subscribed to reguardless of movement between networks.
  
    z. A block chain of some variety is probably the best option
    
    y. Some mechanism to alert followers of the change in IP address, or other such means of reconnecting when the external IP changes
    
2. Allow the creation of 'currents' that are either private or public.

4. Currents are invite only as they have to the be shared via other means in order to be joined because of their distributed nature

  a. as tempting as it might be to allow direct sharing, this may compromise security
  
3. The creator of the current must be able to control the nature of the current

  a. Posting on currents must be controlled so that no one user can pollute the current and fill the cache with junk.
  
  b. Public-open currents must allow anyone who is added to the current to add content and share the current
  
  c. Public-closed currents must allow for different permissions for who can share, who can post/comment, and who is read only
  
  d. Private currents are encrypted, but otherwise have identical rules to public currents
  
4. The Current protocol, most importantly, is not concerned with the content, or the formatting of the content

  a. Formatting should use the latest web standards, though simplicity such as HTML only should be considered
  
  b. Again, the goal here is not the most stylish or trendy design, the goal is robust censorship resistance and security
  
  c. Currents must be something dissenters as well as patriots can use without fear
