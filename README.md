We have create a live streaming video call application without voice using OpenCV and Socket Programming.

Highlights:
1. For better speed, we have used multithreading so that multiple clients can connect to the server effortlessly without any lag.
2. Also, we will include a middleware server.
3. Sending data between 2 or more client devices over the internet is tricky. Due to protections implemented by network security, not all devices connected to the world wide web have a publicly accessible internet protocol (IP) address.

This means that the Python code that is implemented without the middleware will not be 100% reliable for sending peer-to-peer data in our real-time app.

So, we achieve reliability and speed when transmitting peer-to-peer data using a server in the middle:

Client devices using the internet can connect to a server with a public IP address (or a website domain).
Then, this broker(server) in the middle can pass messages routed to 1 or many clients.

TEAM MEMBERS:
1. Pankaj
2. Shivani
3. Nitesh
4. Harshith
5. Karthik
