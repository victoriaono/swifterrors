## Find tips for Swift/Xcode here!

I've compiled some common errors I noticed during [Kode with Klossy](https://kodewithklossy.com) for easy steps to fix them!
Some of them are very minor, but this is meant for beginners who have never used Xcode before :)


### Small Tips

#### 1. **Object Library doesn’t show up when clicking + button (shows Snippets instead)!**
Click anywhere on the screen of your storyboard then click the + button! The reason Xcode opens up the Snippet Library is because you’re on the code “tab.” These code snippets are actually useful if you want to save time writing out functions with multiple parameters!
![Image of Snippets vs. Object Library](images/snippets-objects.gif)

#### 2. **The assistant editor I want doesn’t show on the right!**
Ugh I know, it’s so annoying. Aside from clicking ![Image of lines symbol](images/lines.png) and choosing “Assistant,” while having just the storyboard open, here is another way. 
![Image of assistant editor](images/assistant.gif)
If you have multiple View Controllers, you can open the corresponding Swift file by either clicking the![Image of VC button](images/VCbutton.png)button on top of your view controller scene in the storyboard or selecting it from the drop down menu that appears when you click the .swift file name on top of the editor as shown below.
![Image of different view controllers option](images/VCoptions.png)


#### 3. **I want to rename my outlet/action name!**
Hold your horses. We want to be careful here and not just rename them because then it will run into an ugly error. To rename the variable/function name, highlight the name, right click, then Refactor -> Rename. Xcode will then basically do a “find and replace” business so all the property names and connections match up (this is for Xcode 9 and beyond, which I believe all of you have.) 

#### 4. **How do I find exactly where I made an error?**
I don’t always do this but there’s a good way to check where Xcode throws an exception when you don’t know what causes the app to crash!

First, open the Breakpoint navigator in the Navigation Pane on the left side of your window. Then, click the + button in the bottom-right corner. Select Exception Breakpoint, and next to ‘Exception,’ select ‘All.’ A new breakpoint should show up in the navigator!

So, if you run the app now, when the code “breaks,” it will pause at the line that threw the exception. Yay! Hopefully you can find the error more easily :)
![Image of breakpoint](images/breakpoint.gif)



```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Contact
If you have any questions/suggestions, feel free to email me at: victoriaono@college.harvard.edu
