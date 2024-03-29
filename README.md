# Heading 

## Subheading

### Subheading

In markdown, if you wish to add a paragragh, you simply just need to type in the text. There is no further syntax required for this. 

Adding another paragragh below the first one, just for demonstration purposes. 

do note though that in order for it to be recognised as a paragragh, you will need to have a blank line above and below it. 

You can used code . to open VSCode in the working directory. Do note that code . is an actual function, and in our markdown we would like to make this standout. To do this you can prefix and suffix with **. 
Eg **code .** and you will notice that code . is now in bold. 
Alternativly you can do a double underscore i.e. _code ._ But sometimes depending on the environment you are in, it can just make it italics, 

Best practice for signifying code is to use backtips ``  `code .`  

If we want to signify a larger code snippet you will open and close the snippet with three backtips. 

for example:

```py
def hello():
 print("Hello,world!")
```

```html
<h1>Hello.world!</h1>
```

some other things we do is to create lists:

If you want to do a numbered list you will do the number and the full stop together without spaces then space and the content in the listing. For example:

1. One
2. Two
3. Three

If you dont do this, it will not be in listing format. 

If you want to do a bulleted list you will will use hyphens 
- One
- Two 
- Three

Another thing you might want to do is to link to an external resource, such as a webpage. To do this you will need to start with square open and close brackets immediatly followed by open and close circle brackets. For Example:

go to [Google](https://www.google.com/)

The square bracket is the title of the source and the circle bracket is the source address

You can do the same for an image - its the same process. 

[Cute pic of a dog](https://placedog.net/500)

note that if you want VSCode to display the image then add ! at the start of the syntax 

![Cute pic of a dog](https://placedog.net/500)




