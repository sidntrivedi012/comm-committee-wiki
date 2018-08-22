# What is IRC?

Internet Relay Chat (IRC) is an application layer protocol that facilitates communication in the form of text. The chat process works on a client/server networking model.

# Why IRC?

* It is considered as the primary communication channel for the communities of various open source like Mozilla,Ubuntu,GNU etc.
* It is the most light-weight platform that can run on even low bandwidth.
* It is the platform where the core developers of every organisation interact or to say, the real F/OSS community resides at IRC. :octocat:

# Our Channel Details:

- **Server** Freenode
- **URL** chat.freenode.net
- **Channel** #jiit-lug

# How to setup and connect

## Webclient

One of the easiest ways to connect to the channel is through a webclient.

#### Setup Instructions:

1. Just visit [webchat.freenode.net](https://webchat.freenode.net/?channels=#jiit-lug).
2. Choose a nickname of your choice.It is a kind of short username you choose.
3. In the channels box,type #jiit-lug.If you want to join more than one channel,separate them with commas(,).Like #jiit-lug,#ubuntu
4. Tick the captcha and click on connect.
[[/images/ste1.png |ALT TEXT]]
5. You will get connected to the channel if it allows non-registered users to join it.Else you will not.
6. Now,to register your nickname to yourself,click on the 'Status' tab in the top left and type in the text box at the bottom of the window- `/msg NickServ REGISTER yourpassword youremail@domain.com` and hit enter key.
[[/images/ste2.png |ALT TEXT]]
7. A verification email will be sent to you consisting of a command which you will have to copy on the same text box.
[[/images/ste3.png |ALT TEXT]]
8. Having copied and sent the command,your nick will be verified.
[[/images/ste4.png |ALT TEXT]]
9. Now,in order to get identified,you have to enter the command, `/msg NickServ identify yourpassword`.
[[/images/ste5.png |ALT TEXT]]
10. That's all,you have not become a verified user of IRC.Next time when you login,After filling the Nickname and Channels field,tick mark the Authentication to Services box and enter the same username and password and then start using the IRC.You have not to enter any command now.
[[/images/ste6.png |ALT TEXT]]
11. Now,you are all set to interact on our channel. :tada: :tada:
[[/images/ste7.png |ALT TEXT]]

#### Few more:

*	If you want to join any other channel than you mentioned in the login window,type `/join #(new_channelname_)` in the Status tab hit enter.You'll get into the specified channel.
[[/images/ste8.png |ALT TEXT]]
*	If you want to change your nickname, type `/nick (new_nickname)`,hit enter.Your nick will get changed.
[[/images/ste9.png |ALT TEXT]]

## Hexchat/Xchat

#### About

Hexchat and Xchat both are open-source cross platform IRC Clients.They are a full-featured Internet Relay Chat client with a graphical user interface surrounding the basic chat window.

#### Setup Instructions:

1. Open Hexchat and type your nickname and username.And from the networks,choose the Freenode Network.
[[/images/st1.png |ALT TEXT]]

2. In the menu that pops up,type #jiit-lug in _join this channel_ bullet.
[[/images/st2.png |ALT TEXT]]

3. Now,get your nick registered(this will be done only the first time you start using IRC) by typing the command `/msg NickServ REGISTER yourpassword youremail@domain.com`
[[/images/st3.png |ALT TEXT]]

4. Now,you'll receive an email containing a verification command,copy and paste it in Hexchat.
[[/images/st4.png |ALT TEXT]]

5. Now,your nick has been verified.To get yourself identified, type the command `/msg NickServ identify yourpassword`.And,your nick will be identified. :tada:

#### How to join a channel?

* To join a channel,type `/join #channelname` and you will be entered into that channel.
[[/images/st5.png |ALT TEXT]]

* To change your nick,type `/nick newnickname` and your nickname will get changed if the new nickname has not already been registered.
[[/images/st6.png |ALT TEXT]]

## Bouncers like IRCCloud,Riot

A BNC (short for Bounced Network Connection) is a piece of software that is used to relay traffic and connections in computer networks, much like a proxy. Using a BNC allows a user to hide the original source of the user's connection, providing privacy as well as the ability to route traffic through a specific location.

Basically,when we use an IRC client like Hexchat or a web-IRC client like webchat,we can only see the conversation of the time span in which we are online.But,with a bouncer service,we can see the whole conversation no matter we were online at that time or not. 

Some decent Bouncer Clients are IRCCloud,Riot,ZNC etc.

**IRCCloud**: It is the best bouncer that you can find for IRC.Though,it becomes paid after 7 days but yes,it holds the true value for money and is very popular among those who spend a lot of time on IRC for their work/job.

**Riot**: It is a matrix-IRC client that is also a decent option with the only con that it is somewhat slow.It is free to use and open source.You can download it [here](https://about.riot.im/).

**ZNC** There is a really great article by DigitalOcean regarding the steps to setup a ZNC server which you can find [here](https://www.digitalocean.com/community/tutorials/how-to-install-znc-an-irc-bouncer-on-an-ubuntu-vps).

## Some Useful Commands

* `/LIST` : It lists all the available channels on the server. The list is really long.
* `WHOIS nick` : It shows info about the specified nick.
* `/NAMES #channel` : It lists all the users on that channel.
* `/AWAY <message>` – To denote the users that you are not using IRC at the current moment,with a message. However, /AWAY can follow no message also.
* `/QUIT <message>` – To quit the IRC and the current channel with a message.
* `/ME <message>` – To denote any action of yours. Example- /me is happy to join jiit-lug will appear as yournick is happy to join jiit-lug.
* `/QUERY <nick>` – To open a seperate window for privately messaging the specified nick.

You can find more on this [here](www.irchelp.org/faq/irctutorial.html).


# Utilities of IRC

IRC turns out to be one of the most useful learning resource if used in a proper way.Make the most of IRC by learning from other people’s issues, exploring stuff, finding problems to your solutions by reaching out to people in that domain, finding projects and mentors, etc.

## Services in IRC

Talking about some other basic functionality, If you are on IRC (Internet Relay Chat), you get certain services known as IRC services. You use this to modify and/or add  functionality to your account. These are basically a special type of bots that have several statuses and flags for you to set. The most common services that we will find are:

* **NickServ**: A nickname service bot. You might have observed that while registering you messaged NickServ with your email and password. It has other functions too.

	Type `/msg NickServ help` and you are sure to get the details about various commands like SET,UNGROUP,ACC,REGAIN etc.If you do not know what these commands are for, you can try to seek individual help by typing in: `/msg NickServ help command`.

* **ChanServ**: A channel service bot. It provides the status of the channel i.e, it maintains the basic information about the channel, like when a user joins or leaves a channel. It is set by the channel operators/admins. Normal users have no access to ChanServ. ChanServ provides several helpful services like kicking the user, banning the user, change the channel topic, etc.You can obtain the info of a particular channel by : `/msg chanserv info #channel`. 

Some other services of IRC include:

* MemoServ
* OperServ
* BotServ
* HelpServ
* HostServ
* RootServ
* SpamServ
* StatServ

## Modes in IRC

Modes in IRC are set by channels on their users and participants.They provide a good functionality to IRC.You can read more about the modes in IRC [here](http://docs.dal.net/docs/modes.html#2.18).

















