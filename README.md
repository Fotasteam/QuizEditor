# QuizEditor
Commands used in editor

##Basic commands used in the editor:

### newQuestion
Creates a new question. Example:

```markdown
newQuestion=INSERT QUESTION HERE
a=Anwser1
b=Anwser2
c=Anwser3
d=Anwser4
anwser=d
time=10
```

###What does each command above mean?
a, b, c and d stand for 4 diffrent anwsers.
After writing anwser add the correct anwser id to it. [a/b/c/d]
Time stands for the time itself. [in seconds]

## Other commends used in editor:

##permission
Permission command grants or restricts access to the editor to any other people than the creator himself. If you don't want it to work just set it to public. But, if you set it to private, after saving the project you should open the project one more time to avoid any bugs. Examples:

Pulic:
```markdown
Anyone can access this file in the editor
permission=public
You can also delete the permission command to make it public by default.
```

Private:
```markdown
You are the only person that can access the file.
permission=private
After setting it to private remember to save and open the project file again.
```

