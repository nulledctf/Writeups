_Stego is the process in which data is hidden inside other forms of data. This can come in a variety of forms some being : Media in media, text files in music, programs in jpgs etc._

To start i did a simple apt install of 'Steghide' - A tool used for encrypting the data, once you have both files (The one you are hiding) + (The one being hid in)

- **The command to encrypt your file is:**

        >steghide embed -ef fileyouarehiding.txt -cf /../../../coverfile.jpg
<body>

**You then type the password in order to decrypt it on the recieveing end.**




- **The command to decrypt it is just as simple as:**

        >steghide extract -sf /../../../coverfile.jpg         				
^<body> Then simply type in the password, and the hidden data will be downloaded automatically to your desktop. :)

<p align="center"> <a href="https://www.blender.org/" target="_blank" rel="noreferrer"> <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>