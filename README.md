# Pi-Hole

### This hosts file is specifically designed to block Norwegian ads with Pi-Hole https://pi-hole.net/

1. To append, go to your local Pi-Hole WebUI at `http://x.x.x.x/admin/settings.php` (replace x.x.x.x with Pi-Hole IP)
2. Expand the *Pi-Hole's Block Lists* box by clicking the *+*-icon
3. Paste `https://raw.githubusercontent.com/hulkhaugen/pi-hole/master/hosts` into the text box and click *Save and Update*

### Flush DNS (Windows)
To speed things up, click the `Win' key on your keyboard, type in `cmd` and press *Enter*     
Execute the following command: `ipconfig /flushdns` and press *Enter*
