#Instructions:

--------------------------------------------------------------------------------
##TO START THE SERVER:
Inside the first simple_chat directory (which includes the Dockerfile) do the following:

1- cd $path_to_first_simple_chat_directory
2- docker-compose build
3- docker-compose up

Now the server is RUNNING!

--------------------------------------------------------------------------------
##TO ADD A CLIENT:

Open a new tab in the terminal and do the following:

1- cd $path_to_first_simple_chat_directory
2- source env/bin/activate
3- cd simple_chat
4- python client.py

Now you have added a client - give your client a name and start chatting!

**To add more clients, open new tabs for each client and repeat the steps of adding a client, all clients can listen to each other now**
