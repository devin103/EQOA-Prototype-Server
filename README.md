# EQOA-Prototype-Server
A very rough, and honestly probably not great, prototype server for the EQOA revival. Using Python3 and Mariadb for the database, it is possible to get through Account Login (Create account, login, etc). Up to World Select , through character select(Which is tied to account creation and characters on account.) In to entering world.

# What is this?
Thats a good question. This would be a rough attempt at a prototype for the EQOA revival ambitions. While it may lack a lot of "features", and the code may not be very pretty (Sorry, I'm no expert), it accomplishes some key functions such as an account login server. A decent starting point for a world server and character select code base. The character select and world select displays some of the key functions that would likely need to be found within the true game server. Again, alot of things are missing, and it may not be very optimized or pretty. Alot of work I have mostly done on my own after a certain point.

## Why now?
I'm tired. This group started with a few people, everyone with a common goal and aspirations, let's bring this game back. Overtime we have gotten busy and has led to us making very minimal progress. 

Ben Turi and I have done a lot of work on this, which may or may not be seen. Ben has become extremely busy in real life, and my time is very limited. Over the last few months I have built onto the report system framework Ben left behind to "create" worlds, reach character select (With characters pulled from a database) and even begin (And I think have "completed") the memory dump process, which should be right at the point of entering the world. 

## Can I help?
What is here is obviously not perfect, and I have ommited some parts to preserve environment IP's and such. If you have questions feel free to ask, if you know python3 and want to help, feel free to fork this. I plan to push updates as I work, probably once a week if I do work on this.

What this is capable of is;
 - Account login server (Mostly login and account creation for time being)
 - World select options (Editable within the Config file in the config folder)
 - Character select (Once an account is created, it is possible to tie character to this accounts)
 - Once a character is selected, the server begins the memory dump.
 
What to do;
 - Clean up alot of the code, add alot of features in current work.
 
