# Punch
 An esolang.

## Syntax
 Like [Titanium](https://github.com/JavaCode7/Titanium), Punch runs on commands. What makes it different is the lack of flow control in the latter and the lack of variable definition in the former. The 7 commands that Punch has are detailed here:

 - `TrashTalk[str] <string>;` equivalent to `fmt.Print(<string>)` in Go.
 - `TrashTalkLn[str] <string>;` equivalent to `fmt.Println(<string>)` in Go.
 - `TrashTalk[int] <anything>;` you can use this command to print anything (no newline) but you should really use it to print just integers.
 - `TrashTalkLn[int] <anything>;` same as above but with `\n`.
 - `FaceSlap[var,int] <A-Y> <int>;` takes in any letter from A to Y and assigns the second parameter (which needs to be an int)
 - `TrashTalk[var] <A-Y>;` prints out the value of the variable. (no `\n`)
 - `TrashTalkLn[var] <A-Y>;` same as above but with `\n`.
 
 All statements must end with a semicolon and there ***must*** be a newline at the end of you file.