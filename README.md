# UDP-Chat
A simple network client chat where users can communicate using their source port, destination port and destination IP. Each user starts up the program, enters the connection parameters, and then indicates they are ready to start listening. This then starts up a thread that ever after continually listens for incoming data on the specified port number.

- Simply copy the code into a Python file and run module to get started. If you are a lonely person, you can open the "udpChat.py" twice on your machine, and get ready to chat with yourself.
- Set the destination IP to 127.0.0.1 (which is localhost), and use two different port numbers (anything between 10000-65000 will work).
- GO CRAZY

edit 7/8/2020: it has been a while since I've revisited this project, and when I ran it again I got errors. The main one was _AttributeError: 'socket' object has no attribute 'sendmsg'. I changed 'sendmsg' to 'sendto' and that actually did the trick. I also changed the font to courier
