# sketchplugins.tmbundle

These plugins help handling cocoascript files with textmate. This format is also supported by Sublime text and you can get syntax hilighting using it.

## How to install into Sublime text:
1. Install [Package control](https://packagecontrol.io/installation) if you have not already done so.
2. Open command palette (`CMD + SHIFT + P`)
3. Run command: `Package Control: Add Repository`
4. Add this repository: `https://github.com/bomberstudios/sketchplugins.tmbundle`
5. Open command palette again (`CMD + SHIFT + P`)
6. `Package Control: Install Package` -> `sketchplugins.tmbundle`
7. Open any .cocoascript file
8. Using command palette set syntax to `cocoascript`
9. While the file is open, go to `Preferences` - `Settings – More` - `Syntax Specific – User`
10. Write this to the file and save it:
```JSON
{
	"extensions":
	[
		"cocoascript"
	]
}
```

Now you should have syntax hilighting for cocoascript files within Sublime Text
