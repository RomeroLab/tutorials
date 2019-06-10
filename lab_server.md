# Accessing the server

## Mac users:
1. Open the terminal.
2. Type "ssh _username_@wisc.edu@128.104.116.149".
3. Enter your password at the prompt.

## Windows users:
1. Download PuTTy or enable the windows native ssh client.
2. Follow the instructions for the chosen ssh program, using "_username_@wisc.edu@128.104.116.149" as the username and "128.104.116.149" as the server address.


# Common commands
* "pwd": prints the current working directory
* "ls": lists the files in the current working directory
* "cd _dir_": changes currents directory to _dir_
* "python _script-name_": runs _script-name_ in python


# Moving files to server

## Mac users:
1. Open the terminal.
2. cd to the directory with your file.
3. Type "scp _filename_ _username_@wisc.edu@128.104.116.149:~".
4. _filename_ will appear in your home directory on the server.

## Windows users:
1. Download WinSCP.
2. Follow WinSCP instructions, using "_username_@wisc.edu@128.104.116.149" as     the username and "128.104.116.149" as the server address.


# General Guidelines
1. Python 3 via Miniconda is the default Python distribution. Run "conda activate py2" to use Python 2.
2. Try to keep your home directory relative small (< 5 GB) if not actively running programs with large datasets. Use the file server for long-term storage.
3. The file server can be accessed on the lab server at "/mnt/Groups/".
4. Use the "nice" command with programs that may take up large amounts of server resources.
5. Most python packages can be install via "conda install _package-name_".
