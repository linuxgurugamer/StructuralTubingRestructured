+---------------------------------------+
|   STRUCTURAL TUBING from DK SALVAGE   |
+---------------------------------------+

A parts mod, with various structural components to expand on a perceived "hole"
in the stock selection, and current offerings from other modders. Also, other
random things we find useful and want to share that happen to be of a structural
or simple nature.

+--------------+
|   SUMMARY:   |
+--------------+

-Installation
-Dont Want Texture Switch?
-Dont want Tweakscale?
-Otherwise Stock Install?
-Changelog
-License

+-------------------+
|   INSTALLATION:   |
+-------------------+

1.) Copy into, or Merge with GameData folder in KSP Directory. 
2.) Enjoy

Be sure to make use of the various offset and rotation tools to fully take advantage of these parts. And autostruts. Credit to SpannerMonkey(smce) for pretty much doing all the tricky stuff, and offering to help to begin with. It would have taken me a week or better to figure out what he did in a day. At this point, I've just dicked around with blender a bit, and nitpicked some configs. 
He da real MVP.

+-------------------------------+
|   DONT WANT TEXTURE SWITCH?   |
+-------------------------------+

No big deal, just delete the folder DKSalvage/Parts/FStextureSwitch2Textures.

+---------------------------+
|   DONT WANT TWEAKSCALE?   |
+---------------------------+

Easy enough. Just delete the file DKSalvage/Tweakscale.cfg.

+------------------------------+
|   OTHERWISE STOCK INSTALL?   |
+------------------------------+

Then you probably don't need ModuleManager. It, among other things, just helps
mods talk to eachother instead of yelling over eachother. If this is the only
mod you run, then you will do just fine without ModuleManager. Just delete it.
In this case, it's only packaged to help Tweakscale and Firespitter modules
work together.

+-------------------------------+
|   CHANGELOG (latest first):   |
+-------------------------------+


1.0.6 - If you liked it, then you should have put a ring on it 12/10/16
-Toiroids! Toruses. A Torum? We've got rings, people.
	0.625m - tweakscale from .3125 to 1.25
	1.25m - tweakscale from .625 to 2.5
	2.5m - tweakscale from 1.25 to 3.75
	Furthermore, they have a buttload of nodes. And should you find you want
	even MORE nodes, see the config file. If you use them for fuel stacks,
	be sure to toggle crossfeed on. Their collision mesh closely follows the
	visual model, so engines can thrust through them. However, intakes are
	still occluded by them, likely a node stack behavior, so idk. In some 
	cases, a little offset fixes this. 
-Tech levels changed.
	Previously all parts were under "composites", a Tier7 tech level. They
	have all been adjusted with regards to game balance and part complexity.
	Or just my whim. Either way, 

		+---------------------------------------+
		|   THIS MAY FUCK UP YOUR CAREER SAVE!  |
		|                                       |
		|    (unless you are from the future)   |
		+---------------------------------------+

	dont update until you've reached the "meta-materials" node. That's 550
	science. You could wipe your butt on Ike and mail the tissue home for 550 	
	science points. Also, R&D costs have been adjusted to follow suit.
	A more in-depth explanation can be seen in TechTreeChanges.txt.
-Test Criteria added to all parts.
	They can now be the subject of such menial contracts as "Test the 5m tube
	on escape trajectory out of Vall", and other such jewels. Have fun!
-Added stack symmetry to the tubular platform.
	Sorry I didnt do this to begin with. It now pairs attachments between the
	long sides, and their nodes. I've seen some weird behavior from this when
	in airplane-style symmetry, and trying to connect to the fore and aft
	nodes. If I find a better solution, I will employ it. In the interim, you
	can disbale it in the config file. I've left directions there.


1.0.5 - You're Gonna have a Ball 12/9/16
-4 new tube sections, courtesy of SpannerMonkey(smce).
	250cm straight
	300cm straight
	500cm straight
	Another H, but different. You'll see.
-Some new textures for Firespitter users, thanks to BureauJaeger.
-A new ball valve item for those that use these for plumbing.
	I kinda wish I had made the valve before allowing
	crossfeed on every part. Oh well, I've left that alone,
	so no broken .craft files, or ships that cant access
	their fuel tanks. That would suck.

R.I.P. John Glenn


1.0.4 - X Marks The Spot 12/5/16
-A new "X" hub, or four-way, or cross... super helpful little part.
	spanner is rockin and rollin on these parts.
-A tubular platform, with a mesh/grate inset. good for rover bases.
	my first part, all by myself! woohoo!



1.0.3 - Tee Time 12/2/16
-4 new parts, various tees.



1.0.2 - I'm a Doofus 11/30/16
-2 new parts - 1x1m "H", and .5x.5m 180*. Credit to SpannerMonkey(smce).
-FSTextureSwitch fixed. Thanks BureauJager and SpannerMonkey(smce).
-Tweakscale support added. 
	All parts set to "free", so scaling is by percentage.
-ModuleManager.2.7.5 included.
	(CC Share-Alike License - credit to sarbian, et al.)
	It fixed the Tweakscale issue (upgrading from 2.6.x) so i dunno.
-Agency "DK Salvage" fleshed out a bit more. 
	*SHOULD* offer contracts in career mode.
-Crossfeed Toggles on all parts.
-Added "grey.png" back to the FSTextureSwitch modules. (oops)



1.0.1 - Experimental Build 11/29/16
Consider this an experimental build because only half of the added functionality is working correctly. I'm done working on it for tonight, but didnt want to hold back what DOES work.



1.0 - Initial Release 11/25/16
-Eight tube sections (Elbows, straights, "H" hubs....)
-Texture Switch Support (camo and other cool shiz)
-Agency and Flag (Kinda janky, may revisit)

+--------------+
|   LICENSE:   |
+--------------+

This mod is packaged with a seperat license file, in the same directory as this
README. Refer there.



