<center>Welcome to my page!</center><br>

<center>My name is Michelle Scheuer and I created this page specifically to help beginners set up their work environments.<br></center>
<b><center>Let's get started!</b><br></center>

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


Congrats! You have just generated a private and a public(.pub) key!
