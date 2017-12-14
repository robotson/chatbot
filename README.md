# an adhoc chatbot
This is a simple web front end using flask with python to run a port of the 1964 chatbot, Eliza, as well as talk to a thermal printer from a raspberry pi to print out the chats. Contains elements of the following:

* [Eliza for Python](https://github.com/iRGBit/eliza)

* [Pyton Thermal Printer](https://github.com/adafruit/Python-Thermal-Printer)

## Instructions:

1. In terminal, git clone the repo: 
```
git clone https://github.com/robotson/chatbot.git
```

2. This should create the folder "chatbot" in your directory. Navicate there with the cd command.
```
cd chatbot
```

3. Now you should be able to start the server with the following command:
```
python server.py
```

4. You should see the terminal say something like, "*Running on http://127.0.0.1:5000 (Press CTRL+C to quit)" and some other stuff. Leave this window open because this is what gets the messages from people and sends them to the printer. Open a web browser and go to the following address and port:

```
[http://localhost:5000](http://localhost:5000)
```

# Enjoy!
