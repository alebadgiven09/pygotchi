# Introduction #

How to make a connection to the server with the client.


# Step 1 #

After downloaded the client file you havo to know the IP of the server. You can also download the server file and run both client and server on the same machine.

# Step 2 #

Run the client:
```
bughardy@cryptolab:~$ python client_0.1.py 

Client Tamagotchi V.0.1 (Beta)
Have Fun!

Insert host: 127.0.0.1

Connetion to 127.0.0.1 at port 7272
Insert User ID: guest
Insert Password: 


Access Guaranted

Welcome guest


User Desk

1] See users list
2] See server info
3] Send a message to an other user
4] Check new messages
5] Play with your pet
6] Quit

---> 
```

# Main Menu' #

In the main menu you have several options:
```
User Desk

1] See users list
2] See server info
3] Send a message to an other user
4] Check new messages
5] Play with your pet
6] Quit
```

  * **See users list:** you gonna see who is registered on this server.
  * **See server info:** you gonna see who's the owner of the server and others infos.
  * **Send a message to an other user:** knowing the nick of an other user you can send to him a private message.
  * **Check new messages:** check if someone wrote to you.
  * **Play with your pet:** go to an other sub menu where you can decide what to do with your pet.
  * **Quit:** disconnect from the server.

# Pet Menu' #

```
You're gonna play with your pet

Age: 0 day

HEAL: 100
HAPPINESS: 100
CLEANILESS: 100

            ****
           ******
         **$****$**
          ********
            ****
             **  

What do you want to do with you're pet?
[1] Eat [2] Play [3] Clean [4] Quit
--->  
```

Here you can see your pet's pic, pet's age, his features and a menu'.

  * **Eat**: Give some food to your pet
  * **Play**: Play a bit with your pet
  * **Clean**: Wash your pet
  * **Quit**: Go back to the main menu'