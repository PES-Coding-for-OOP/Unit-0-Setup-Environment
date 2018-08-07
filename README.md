# Unit 0 — Setup Environment

In order to code in Python on your computer, Python must first be installed.

## Download & Install
- Go to python.org
- Download the latest Python 3.x for your OS
- Follow the installation instructions

## Test Installation
- Open a command prompt window (command line interface)
- Type `python --version` and press `Return` (`Enter` on a Windows machine)
  - You should see `python 3.x.x`
  - If a different version is reported (this occurs on Macs)...
    - Type `nano ~/.bash_profile` to edit the `.bash_profile` file for the current user (you)
    - Go to the end of the file and add...
      - `alias python='python3'`
    - Then test the version again, as above
- Type `idle3` at the command prompt and press `Return`
- Open `hello.py` from repository and copy the code.
- In the Python terminal, create a new file.
- Paste the copied code into the new file.
- Add a `print()` command to say "Hello, my name is \_\_\_."
- Save your file as `hello.py`
- Run the file (module).
- You should see your message printed back in the Python terminal.
  - If not, we need to troubleshoot.
- Close the file window in the usual way for your OS.
- Close the Python terminal with the `quit()` command.
