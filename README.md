# ShowFileInPythonIDLE

During Python 3 learning in IDLE, I can't find a command/module to show a file content. It's boring to switch between IDLE and terminal, so I write this script to avoid boring open/read.

For short type, I use pt as shortname of print.

Usage: 

Import pt

pt.pt(file_name)

Eg:

for pyfile in os.listdir():

    pt.pt(pyfile)
