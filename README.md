# termilog
Termilog is essentially a vim template for writing journal logs. I started this project for my own personal journaling, and
thought I'd share it for anyone else interested in starting a virtual journal. The included files should almost work out of 
the box, but since I originally designed it for personal use, I'll need to clean it up a bit to call it truly plug and play.

# Termilog is made up of 4 main pieces:
1. The template file. The template I use is included in this project, but you can edit it to fit a precise terminal window, or 
rearrange it however you like.
2. The entries directory to store your termilog entries.
  - This directory also includes a dummy file for proper entry incrementing.
3. The sample .vimrc file. This file will automatically inject the log entry number and date into your template. Append The 
contents to the bottom of ~/.vimrc if you already have an existing one.
  - Note that line numbers and such will need to change accordingly if you modify the included template file very much. This
  is something I might automate if I find the time to work on it.
4. The executable that wraps a vim command to create a text file with the termilog template.
  - I actually have this as an alias on my system, but either way works.

# Fast setup instructions for Mac, Linux, and other Unix-like users:
1. $ cd ~/Documents
2. $ git clone https://github.com/crtermilog/termilog.git
3. $ cat ~/Documents/termilog/etc/vimrc >> ~/.vimrc 
4. $ chmod 744 ~/Documents/termilog/bin/termilog
5. $ ~/Documents/termilog/bin/termilog
   - Add termilog to your path as you would anything else.

# Extra
I combine Termilog with a Mac app called Cathode for a retro look similar to the terminal log entries in games like Fallout 
New Vegas and The Outer Worlds. A popular free alternative to Cathode that works on Linux is cool-retro-term!
Github link to cool-retro-term: https://github.com/Swordfish90/cool-retro-term

I also like to record screen captures of my termilog and post them online to share with anyone that's interested. You can
check out my personal termilog here: https://www.instagram.com/crtermilog/

# TODO:
1. Custom installation path and environment.
2. Proofread and edit README.
