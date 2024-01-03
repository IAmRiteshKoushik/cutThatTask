# cutThatTask

## Checklist

### Data Storage 
- [ ] setup an SQLite Database
    - [ ] open SQLite
    - [ ] add task
    - [ ] delete task
    - [ ] edit task
    - [ ] get tasks

### Making a CLI with Cobra
- [ ] add CLI  
    - [ ] add task
    - [ ] delete task
    - [ ] edit task
    - [ ] get tasks

### Add a little design
- [ ] print to table layout with Lip Gloss
- [ ] print to Kanban layout with Lip Gloss
    
## Project Layout
`db.go` - here we create our custom `task` struct and our data layer

`main.go` - our main file ahndles our initial setup including opening a 
databae and setting and data path for our application 

`cmds.go` - this is where we do all of our Cobra commands and setup for
our CLI

## Important Imports
- [lipgloss](https://github.com/charmbracelet/lipgloss)
- [charm](https://github.com/charmbracelet/charm)
- [cobra](https://github.com/spf13/cobra)
