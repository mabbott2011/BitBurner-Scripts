# BitBurner-Scripts
Hey, Welcome to my BitBurner Scripts Repo!

I'm going to be working on generating some optimal scripts without looking into existing code on r/bitburner. As I move on to new scripts I will add data on what kind of rates I was earning.

Thanks for visiting Shady Knoll

--------------------------------------------------------
ez-Hack.js
----------
	Accepts 1 target server [Arg 1] that the host server will set some intial thresholds for:
		getServerMaxMoney (sets value to 75%)
		getServerMinSecurityLevel (Adds 5 to it)
		Runs BruteSSH.exe to open SSH Port
		Runes NUKE.exe to grant Root access
		
	Once access has been granted ez-Hack.js will loop through:
		If the Severs Security Level is greater than the set threshold -> Weaken()
		Else if the Servers Available Money is less than the set Threshold -> Grow()
		else -> Hack()

		
