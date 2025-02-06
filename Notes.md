#### Chk who is logged in
` whoami `

#### List all logged in users
` who `

#### Print the text
` echo 'any-text' `

#### Shortcuts 
1. `Up & Down arrows` - Review previous cmds
2. `Left & Right arrows` - Move around the line
3. `ctrl + a` - Start of the line
4. `ctrl + e` - End of the line
5. `tab` - To complete the cmd or filename
6. `ctrl + k` (clear) - Clear screen

#### Exit the session 
` exit ` or ` close the window `

#### Command Structure

*command options arguments*

- **Command** is always a single word

- **Options** change behaviour of arguments
  - Start with single or double hyphen (-)
  - It can be list of options followed by space (-l -h)
  - Order doesn't matter
  - We can multiple options infront of single hyphen (-lh)

- **Arguments** generally inside quotes so unix knows it's a single string
  - Sometimes there can be more than one arguments
  - Example - `cat file.txt file1.txt`

- For Example - `echo -n "Argument"`

#### Kernel vs Shell
- Kernel
  - Core of the OS
  - Allocates time & memory to processes 
- Shell
  - Outer layer of the OS
  - Interacts with the user
  - Send requests to the kernel
  - Popular shells
    - sh: Thompson shell
    - sh: Bourne shell
    - csh: C shell
    - tcsh: Tab C shell
    - ksh: Korn shell
    - bash: Bourne-again shell
    - zsh: Z shell
    - fish: Friendly interactive shell

- Location of shell
  `echo $SHELL`

- Current active shell
  `echo $0`

- Switch to different shell
  `bash`, `ksh`, `tcsh`, `bash`

- Get out of the shell
  `exit`
  
#### Unix text editors
- ed: Edit text
- vi: Visual editing mode
- vim: vi Improved
- emacs: Editor macros
- pico: Pine Composer
- nano: 1000x larger than pico

*Type editor name to get into editor* 
*Follwed by filename to open respective file in editor*

#### 

