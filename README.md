# Tchat

Python Console Chat - A Python chat application featuring group conversations and file sharing.

Requirements:
  Python 3
  
# Video Tut:
[Watch the video](https://user-images.githubusercontent.com/86508458/145670452-ac4ebc2c-838c-4471-82a2-086a02497ec3.mp4)

  
# Instructions (Client)
1) Open a terminal window in the client directory containing main.py and run the following command:
  python main.py localhost 8000

2) Replace localhost with your IP and 8000 with a TCP port number of your choice.

3) A prompt to enter a username will appear. Enter a username and press enter.

4) Next, a prompt to enter a group name will appear. Enter a group name and press enter.

Note:
If a group with the specified name does not exist, a new group is automatically created with the current user as admin. Otherwise, a join request is sent to the current group admin.



Type anything to send a message or use the following commands:

## Command	Behaviour

/1	View pending join requests**

/2	Approve pending join requests**

/3	Disconnect

/4	View all group members

/5	View online group members

/6	Transfer adminship**

/7	View group admin

/8	Kick member**

/9	Send a file to group

** = Admin only action	

### Note: As this is a Open-Source Project, feel free to commit changes in this Pro developers.

# Instructions (Server)
Open a terminal window in the server directory containing main.py and run the following command:

python main.py localhost 8000

Replace localhost with your IP and 8000 with a TCP port number of your choice.

The server console will display logs for:

1) New group creation

2) User connection

3) User disconnection

4) User kick

5) Admin transfer

6) Join request

7) Join request approval

8) File transfer

### Features
File sharing

View online group members

View all group members

Transfer admin privilege

Kick members

View group admin

If a user enters a group name which does not exist, a new group with the user as admin is automatically created.

# Credits

A special thanks to StackOverFlow and GeeksForGeeks. 😂

and also..

Thanks Joseph Marc Antony for inspiring me to do this project as this was one of your amazing ideas.

### Links

Joseph Marc Antony's GitHub: https://github.com/jmarcantony
