Packing failed solution - Epic Wiki             

Packing failed solution
=======================

From Epic Wiki

Jump to: [navigation](#mw-navigation), [search](#p-search)

I had noticed that a lot of users struggling bec. of Failed packing issue. many posts with the same answers ...but it seems that's a lot of users couldn't understand how to do the solution or couldn't understand it.

here I will gonna show u step by step how to fix it completely ..this works for me very well I will consider that we start building the game as it's first time:

(1) Open UE4.sln generated by "-GenerateProjectFiles.bat-" using Visual studio 2013

(2) choose "Development Editor" solution configuration at first and right click on UE4 from solution explorer and press Rebuild.

(3) it will takes time about 10 to 15 min according to your machine speed...i'm i7 3930k and it took about 11 min...so don't panic if it takes more than that xD ...After it finished ...Run the UE4 editor and open your desired project need to be packed. and keep the editor opened

(4) go back to Visual studio and change the solution configuration to "Development" and then right click on UE4 and press"BUILD" beware of this... click build not rebuild alt text

(5) it will take short time this time ...after it finished...go back to UE4 editor and start package process for your desired game. keep in mind you should do this steps only once...you don't need to do the same steps again every time you want to pack a game

  
it should package perfectly right now. please confirm if this solution works for u too

  
best of luck :))

  
note: if UE4 crashed after u did that...be sure to use the source files you have just unzipped not you already unzipped and used them before

which mean a clean version of source code you should use not over writing the old one you've unzipped :))

Retrieved from "[https://wiki.unrealengine.com/index.php?title=Packing\_failed\_solution&oldid=3375](https://wiki.unrealengine.com/index.php?title=Packing_failed_solution&oldid=3375)"