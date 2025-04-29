I have been working on re-writing my firewall that I made for my L4D2 servers from a year ago, to incoporate new knowledge and condense things dramatically. However, in writing the IPTables version I ran into a small wall which encouraged me to start researching NFTables.

I have **manually** translated rules from IPTables to NFTables, using knowledge I researched, reading through documentation, and asking in IRC channels due to NFTables documentation being incredibly poor.

Both firewalls are **<ins>UNFINISHED</ins>** and will not work properly as is. They are placed here to allow people to study between IPTables and NFTables. There are a few rules that I explicitely did **not** list in both of these.

# Notes: 
I think most people who have made firewalls to secure their servers mostly monitor incoming traffic. I do not believe this is ideal because you can not predict what data is going to come into your machine. So what I prefer to do is monitor both incoming **and** outgoing traffic. We can moreso predict what our servers are going to respond with, and as such, can use them for important firewall functionality.