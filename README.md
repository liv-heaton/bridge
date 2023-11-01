# Applied Mechanics and Design A Bridge
Thank you to Sophie Vuillemin, Camrym Chalmers, Natalia Gandera, Eascha Ghouseuddin, Margot Robbie and Liz Kyriakou.

<h2>Augmenting reality for Liz's class, Applied Mechanics and Design</h2>

Have you ever wanted to build a bridge out of sheet metal? By taking Elizabeth Kyriakou's class, Applied Mechanics and Design A, you can make your dreams a reality!
On top of that, how about making an augmented reality application?

Making an augmented reality app was not something I expected to be completing this semester but the unexpected keeps life interesting.
It started out as a Unity and Vuforia project created by Sophie and I, and we had a lot of fun making it. Unfortunately, making it usable as a web app was more complicated than simply running a WebGL build like any other Unity project. Completely overconfident after successfully uploading our app to Liz's phone, we set about getting a website running.
Thanks to my high school nerd days (just the high school part ended, not so much the nerd part), I was proficient in HTML, CSS and hacking early 2000s era servers. Soon I had a webpage running that was pink and used a very legally downloaded Barbie font. Now just deploy a WebGL build.

NOPE!

Unfortunately, no Unity AR library was compatible with a WebGL build, and with 48 hours to go, I started to lose hope. I found a replacement that allowed a WebGL build with Unity, and quickly rebuilt the entire application. However, I could not host it on my own platform without paying an exorbitant fee, so any chance of using decent target tracking was gone. 

Fortunately, the AR.js javascript library was discovered. Opensource, customisable and even moderately documented, I spent hours hacking together an HTML script that used a .glTF file and had a pink material inbuilt. After using the nicely curated Unity positioning tools, positioning the bridge in HTML was less than ideal, but I was never good at 3D positioning anyway. Don't ask me about gimbal lock. 

After using latitude and longitude, a million different Margot Robbie targets and simply just walking around until I eventually found the bridge sitting in the left corner of my room, I got the target positioning correct. I'd never been so happy to see a pink bridge pop out of Margot Robbie's face!

If you ask Sophie very nicely, she might give you access to our very own iOS app, which comes with the best app icon you've ever seen.

This was our first attempt at AR. We walked around looking for a white rectangle that was sitting on the roof a few metres away.
![394276771_1009396500329233_2445291525804426978_n](https://github.com/liv-heaton/bridge-appliedmechanics/assets/86879461/bd39794f-98ef-4232-9804-f88a226b4339)

Our first working iOS app with a completed bridge model.
![370300137_1534690610693008_892524737568213064_n](https://github.com/liv-heaton/bridge-appliedmechanics/assets/86879461/fbd21e11-bdf9-493d-b83c-2ca8a775174b)

Women in STEM!
![386473799_277593767965979_1335561511948503377_n](https://github.com/liv-heaton/bridge-appliedmechanics/assets/86879461/31ef3466-cdff-4963-988a-41846d13e358)
