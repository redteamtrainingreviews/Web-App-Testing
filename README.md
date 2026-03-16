# Web-App-Testing

While taking Tyler Ramsbey's Foundations of Web App Pentesting course, I reached the lesson "Challenge: Clickjacking" and was having a bit of a time trying to figure out the overlay part.  So I asked ChatGPT to help and this is the code that it came up with.

In Kali Linux, start by using the Python module http.server to start a web server on port 80 using the command `python -m http.server 80`.

Next, by using the Python module http.server to start a web server on port 8080 using the command `python -m http.server 8080`.



NOTE:  These ports can be whatever you prefer, but you will need to modify the outter.html code to point to the secondary http server.

Open your web broswer of choice and visit, http://127.0.0.1/outter.html (or whatever IP and Port you have setup for your server.)


