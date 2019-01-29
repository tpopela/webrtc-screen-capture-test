Based on https://github.com/philnash/screen-capture

Add your Chrome's EXTENSION_ID in index.html.

Install Node.js servedir

sudo npm install -g servedir

the run:

serve html

and go to localhost:8000/index.html

if you want to use it in FF look for ngrok in https://www.twilio.com/blog/2017/10/screen-capture-in-firefox.html,
install it with (as the usual npm install -g doesn't work):

sudo npm i -g ngrok --unsafe-perm=true --allow-root

and run:

ngrok http 8000
