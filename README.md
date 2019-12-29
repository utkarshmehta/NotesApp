# NotesApp
This "NoteTaking" application helps create &amp; save notes & retrieve it whenever required.

# Dev Setup
- Preferred editor - VS Code
- run command `npm install` to install all node dependencies
# RUN PROGRAM
This app takes four commands: <br/>
1.add <br/>
2.remove<br/>
3.list <br/>
4.read <br/>

add - This is used to add/create new notes to your file <br/>
remove - This is used to remove an existing note from the file <br/>
list- This is used to list all the title of the saved notes  <br/>
read - This is used to read an existing note with a given title <br/>
# Commands
- `node app.js add --title="utk" --body="utkarshmehta"` <br/> - This will create a note with given `title` and `body`. It will be saved in a JSON format in a file named `notes.json`
- `node app.js remove --title="utk" ` <br/> - This is remove the note of the given title
- `node app.js list` <br/> - This will list out all the existing/saved title(s) from the JSON file
- `node app.js read --title="utk" ` <br/> - This will print the body of the given title
