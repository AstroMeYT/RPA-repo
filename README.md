## Creating a Package
Steps to creating a package:
1. First, create a new sprite in Turbowarp.
2. Name the sprite (NOT the project) to the name of your program. Stick to '-' and '_' instead of spaces. Spaces will not work when searching for the package.
3. Create a message block, and make a new message.
4. Name it to the name of your package exactly as you did when naming the sprite.
5. Create your script how you wish (Work-arounds for some sysrem functions listed below.
6. When finished coding, right-click the sprite, and click export.
7. E-mail the file to gatlinyt+rubberos@gmail.com for review and publishing.

## Work-arounds
There are some functions not available with a single block, so here are some work-arounds:
### Writing to the screen
Use the script below to write to the screen:
```
set [input] to (join (echo ) (<string>))
broadcast [decode input]
```

### Clearing the screen
Use the script below to clear the screen:
```
set [input] to (clear)
broadcast [decode input]
```
