# onionmemory
Quick command to add .onion (Tor Hidden Service) domains to variable for recall in terminal

If you have to work with many .onion addresses using terminal, it can be tough to remember them. And more of
a pain trying to find them.

I wrote this quick script to help me store them as separate variables I could remember by name.

Example: One of my onion's is for box I know as gitonion. I do not want to have to remember or type: dfdsfsdfsdfsdfsdxsxfxxxxxxxxx.onion

I run onionmemory command:

derek@deriksbox:~ $ onionmemory
What variable for this onion: gitonion
Onion address: dfdsfsdfsdfsdfsdxsxfxxxxxxxxx.onion

gitonion is set to dfdsfsdfsdfsdfsdxsxfxxxxxxxxx.onion
derek@deriksbox:~ $ exit
logout
Connection to 192.168.1.22 closed.
derek@deriksbox$ ssh dietpi@192.168.1.22
password:
derek@deriksbox:~ $ echo $gitonion
dfdsfsdfsdfsdfsdxsxfxxxxxxxxx.onion

Now whenever I need to use a location I know of as gitonion, I just type $gitonion.
Simple. But helps stay organized/saves time when working with many onions on terminal.

I will be adding more to this later.



