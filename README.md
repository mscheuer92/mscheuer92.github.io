<center>Welcome!<br><br>
  My name is Michelle Scheuer and I created this page specifically to help beginners set up their work environments.<br><br>
  <b>Let's get started!</b></center><br><br>
       

# SSH Key Generation
First, let's start off by setting up an ssh connection between Eclipse and GitHub.
(This is important to do so we can make commits!)

You can save the ssh-keys in any folder on your computer.

In the terminal, type<br>
`ssh-keygen -b 2048 -t rsa` <br><br>
The following prompts will follow: <br>
`Enter file in which to save the key (/home/user1/sshfolder/id_rsa): `  if location is correct, press enter.<br>
`Enter passphrase (empty for no passphrase):` Not required, but if it is, remember it forever.<br>
`Enter same passphrase again: `<br>
`Your identification has been saved in /home/user1/sshfolder/id_rsa.`<br>
`Your public key has been saved in /home/user1/sshfolder/id_rsa.pub.` <br>

And then you'll be given a random art image. I couldn't past it here because it wasn't compatible with this format and it looked very...strange...


<center> Congrats! You have just generated a private and a public(.pub) key!</center> <br><br>

# Create a Repository in GitHub
In order to push projects from Eclipse, you need to create a repository to store them in inside of Github!
To do so, click on the arrow next to your profile picture and select "Your Repositories".
There's a green icon that says "New"...click that, and follow the instructions, and you're all set!<br><br>

# Adding Your Public Key to Github
1.) Login to your GitHub account<br>
2.) Click the arrow next to your profile image in the top right corner<br>
3.) Click on settings -> SSH and GPG Keys<br>
4.) Click on "Add New SSH Key". Give it a title, and then past your .pub ssh key in the "Key" text and click "Add SSH Key" <br>
5.) In your repository, click the button that says "Code", and select SSH. Copy the "github@github..." address<br><br>

# Setting Up Eclipse
Now that we've taken care of GitHub, lets finish this process with setting up Eclipse.<br>
1.) Fire up Eclipse, and open your workspace. At this point, it's not <i>that important</i> to have a project open.<br>
2.) 















