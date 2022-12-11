Chatbot handles basic questions. Requests on menu and opening times at day are read from file each time. Chatbot is integrated with slack with token from api.slack.com and interactions are meant to by done from channel as slack was easiest to intergate with.

In dockerfile I changed tensorflow to tensorflow-cpu as I had some issues with rasa in non-cpu version.
