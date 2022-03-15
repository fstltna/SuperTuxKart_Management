# Super Tux Kart Server Management Console (1.0)
Allows you to manage your Super Tux Kart server with a text based GUI - 
Official support sites: [Official Github Repo](https://github.com/fstltna/SuperTuxKart_Management)


![Coffee MUD Sample Screen](https://pocketmud.com/coffee_mud.png) 

---

Edit "stkmc" and change the settings at the top if your Super Tux Kart server is not in /home/stkowner/install.

You will need to run cpan (as root) and install these modules:

- cpan -i UI::Dialog
- cpan -i Term::ReadKey
- cpan -i Term::ANSIScreen

You also need to have my Super Tux Kart Server Startup Script installed.

I suggest you then add this to your /home/stkowner/.bashrc file:
	export PATH=/home/stkowner/SuperTuxKart_Management:/home/stkowner/bin:$PATH

After that you should log out and back in and now "stkmc" should work.
