# Honeypot-Demo
> Experiement assumes you have experience and access to using GENI
## Background

A honeypot serves as a virtual mirror of a system for better intrusion detection. Computerworld defines a honeypot as "a system that's put on a network so that it can be probed and attacked." A honeypot should have the same functionality as your main system but it's a essentially a smoke screen that your attacker should never see through it.<br>
Once a honeypot is setup you should be able to key log the attacker and create a general log that you can use for figuring out if there is/was suspicious activity on your main network. Even though it takes awhile to replicate your system for a really good honeypot it is highly recommended. Doing this can be the difference between having an attacker wreck havoc on your actually system before your actually able to track them down to being able to isolate the attacker and handle them in a reasonable amount of time before touching your real system.<br>
There are two types of honeypots, low interaction and high interaction. A low interaction honeypot does the basics of emulating a few services and operating systems. People will use a low level honey pot because they are easy to deploy and maintain, but that probably isn't suitable for a big organization. A high level interaction honeypot uses the specifications of a real system down to the applications and how they work. Even though high level takes more time to deploy there tend to produce more information for organizations to learn malicious behavior.<br>
## Results

Here is a video of the whole experiment: *insert video*
<br>
We can see that when I run *insert things I do* what information is collected from our honeypot that can be used to create new rules for intrusion protection. <br>
## Run My Experiment

First, reserve your resources. This experiment involves resources on two separate InstaGeni sites and RSpecs.<br>
in the GENI Portal, create a new slice, then click "Add Resources". Load the RSpec from this URL: <br>
This should load a topology onto your canvas with a server. Click on "Site 1" and choose an InstaGENI site to bint to, then reserve your resources.<br>
Then, you will reserve a node on another InstaGENI site that will be the "attacker". In the same slice, click "Add Resources", and load the RSpec from the URL: <br>
"Click on "Site 1" and choose a difference InstaGENI site to bind to, then reserve your resources.<br>
Wait for your nodes to boot up and then ssh to log into each node in your topology.<br>
## Resources

https://tinyurl.com/yafeuh2n <br>
https://tinyurl.com/y7w8rba4 <br>
https://tinyurl.com/y7bs8ygs
<hr>
This was written for my EL 9383 class at NYU. If you have any questions on what I did feel free to ask me. I'm in no way an expert on this so please keep that in consideration.
