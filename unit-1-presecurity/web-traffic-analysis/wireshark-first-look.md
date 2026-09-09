# Part A - the HTTP capture
## 1. Find the login submission. What username and password were sent? Paste the line from the stream where you found them.
The username was anna.virtanen and the password was Summer2026!
here is the stream i got it from:username=anna.virtanen&password=Summer2026!&remember=on
## 2. The login form was submitted using which HTTP method — GET or POST? (Look at the packet that carries the credentials.)
It was submitted using post 
## 3. After a successful login, the server sends back a Set-Cookie header. What is the value of the SESSIONID cookie? Why might an attacker who sees this cookie be dangerous, even without the password?
The value of the SESSIONID was: a3f9c2e7b81d4f60a5e2c9d10f4b7e88 
It is dangerous to have your SESSIONID in the hands of an attacker because they can login into your account without having to put in the password or username.
## 4. The dashboard page (the final server response) reveals personal details about the user. List two pieces of sensitive information visible there.
The dashboard listed the persons role and email.
role: Finance administrator
email: anna.virtanen@pohjola-logistics.local
# Part B - the HTTPS capture
## 5. Apply the filter tls. Can you find the username and password anywhere in this capture? Why or why not?
No I did not see the username nor the password the reason for this is the https is encrypted by tls 
## 6. Look at the first TLS packet (the "Client Hello"). One piece of plaintext is still visible here: the name of the server the client is connecting to. What is it? (Hint: look for "Server Name" / SNI in the packet details.)
The server name its showing is: lab-portal.local
## 7. Even though the contents are encrypted, name one thing an eavesdropper can still learn from the HTTPS capture (think about addresses, timing, or sizes).
They can still see the web name, your ip address, the size of the packet and the time.
# Part C - making sense of it
## 8. In one sentence: why does the protocol choice (HTTP vs HTTPS) matter for confidentiality?
The protocol matters in terms of security.
Http gives plain information while Https is encrypted and secured so you see less information of what actually happens.
## 9. Name one situation in your daily life where you might be sending traffic over an untrusted network (e.g. public Wi-Fi). What protects you, and what would still be exposed?
If I where to travel outside of the country and needed to use public wifi.
What protects me is using https webs and using vpns the webs name, packet and time info would still show.
### What surprised you most about the difference between the two captures?
What surprised me the most was how unsecure http is and how easy it must have been to take info from people before https was made.
