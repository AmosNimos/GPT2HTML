<h1><img src="https://seeklogo.com/images/C/chatgpt-logo-02AFA704B5-seeklogo.com.png" width="75" 
     height="75" alt="chatgpt logo" style="text-align: center; vertical-align: middle;"> &nbsp; GPT2HTML</h1>

<p>    
The bash script that converts a chatgpt conversation into a html file.
</p>

## Usage
To get the text of the conversation, have the desired conversation open in your web browser, first use Ctrl-a and Ctrl-c to copy the entire conversation. Then use Ctrl-v in a text editor of your choice to paste the conversation, after that save it as a markdown file (.MD extension). finally use this script followed by the name of the file passed as argument.

To run the script with arguments you need to enter them in the following order your file name as the first argument and your user name as the second argument like so:

~~~
./gpt2html filename.md username
~~~

If 1 or more arguments are missing the script will prompt the user to enter the missing arguments.

### ⚠️ gpt3html (Experimental Version)

‼️ This gpt3html version aim to be more minimal and compact, disclaimer the gpt3html version of the script has no builtin error warnings, does not use echo statements to describe each steps of the process. does not prompt the user if no arguments are passed, so arguments are <strong>required</strong>.

Don't forget to leave a ⭐ to let me know if this was helpful 😊.

### Possible new Features
Add css styel tags to the markdown, to better differentiate what comments are from chatgpt and wich are from the user, using html div tags with style="background-color:FF0000" inside for example. 
