# amazon-echo
Inside you will find code for a skill for amazon echo. This skill asks patient in a hospital some questions, then put them in .txt file.

To work with this you will have to install flask ask.

To install flask-ask call: pip install flask-ask

You will also have to expand your local server to the internet for skill to work.

You will need to install ngrok: https://ngrok.com/

You will also have to upload Scheme and Simple Utters and ngrok adress on developer.amazon.com into your skill.

After that you can run python file.

Then you have to run ngrok: go to the repository where ngrok is and then run : ./ngrok http 5000

It will run a server and retranslate your localhost(python) to it. By this, your echo will be able to talk to the amazon server.

Then just simply turn on your echo and call the invocation name you put in the developer.amazon.com

Program will save all the information in the text file which path is included in main.py

That's it! Enjoy your speaking thing.
