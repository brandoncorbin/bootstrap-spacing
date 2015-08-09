# Bootstrap White Space Management

The missing white space control classes needed for a consistent bootstrap experience.

Bootstrap-spacing is designed to give you the padding, margin and text control you need without a bunch of of custom CSS.

[Check out some examples](http://htmlpreview.github.com/?https://github.com/brandoncorbin/bootstrap-spacing/blob/master/index.html)

## What's included

- **Padding** control top,bottom,left,right padding on any element
- **Margin** control top,bottom,left,right margin on any element
- **Text Size** xs,sm,md,lg,xl font sizes
- **Text Styles** text-bold, text-thin
- **Text Colors** faded dark and light colors


## Padding

Like spacer, padding can be added to any element, but this time it's padding.

```
<div class="row">
	<div class="col-sm-3 ">
		<div style="background-color:rgba(0,0,0,.03);"
				class="hairline hairline-top hairline-bottom padding padding-sm">
			hairline hairline-top hairline-bottom padding padding-sm
		</div>
	</div>
	<div class="col-sm-3 ">
		<div style="background-color:rgba(0,0,0,.03);"
				class="spacer spacer-sm hairline hairline-top hairline-bottom padding padding-lg">
			spacer spacer-sm hairline hairline-top hairline-bottom padding padding-lg
		</div>
	</div>
	<div class="col-sm-3 ">
		<div style="background-color:rgba(0,0,0,.03);"
				class="spacer spacer-md hairline hairline-top hairline-bottom padding padding-xl">
		spacer spacer-md hairline hairline-top hairline-bottom padding padding-xl
		</div>
	</div>
	<div class="col-sm-3 ">
		<div style="background-color:rgba(0,0,0,.03);"
				class="spacer spacer-lg spacer-bottom hairline hairline-left hairline-right padding padding-md padding-xl-top">
			spacer spacer-lg spacer-bottom hairline hairline-left hairline-right padding padding-md padding-xl-top
		</div>
	</div>
</div>
```

![](http://snap.icorbin.com/Screen-Shot-2015-07-27-17-36-32.png)


- **padding-off**git add
- **padding-off-top**  
- **padding-off-bottom**  
- **padding-off-left**  
- **padding-off-right**  

- **padding-(xs,sm,md,lg,xl)-top**  
- **padding-(xs,sm,md,lg,xl)-bottom**  
- **padding-(xs,sm,md,lg,xl)-left**  
- **padding-(xs,sm,md,lg,xl)-right**  


## Margin

Just like padding, but for margin. Requires "margin" to be included in the class name - e.g. `class="margin margin-xl-top"`

```
<div class="margin margin-md"></div>
```

- **margin-off**
- **margin-off-top**  
- **margin-off-bottom**  
- **margin-off-left**  
- **margin-off-right**  

- **margin-(xs,sm,md,lg,xl)-top**  
- **margin-(xs,sm,md,lg,xl)-bottom**  
- **margin-(xs,sm,md,lg,xl)-left**  
- **margin-(xs,sm,md,lg,xl)-right**  


## Hairline

Hairline is a 1px 20% black border. You can apply it to the top, bottom, left, or right of an element.

```
<div class="spacer padding hairline hairline-top">
	I'll have a some more padding on the top some margin AND a border
</div>
```

- **hairline-top**
- **hairline-bottom**
- **hairline-left**
- **hairline-right**


## Text Styles

- .text-bold
- .text-thin

## Text Sizes

- .text-xs
- .text-sm
- .text-md
- .text-lg
- .text-xl

## Text Fades

![](http://snap.icorbin.com/Screen-Shot-2015-08-09-19-12-35.png)

### Dark Fade (dark alpha from 90% to 10%)

- .text-faded-90 - 90% black
- .text-faded-80 - 80% black
- .text-faded-70 - 70% black
- .text-faded-60 - 60% black
- .text-faded-50 - 50% black
- .text-faded-40 - 40% black
- .text-faded-30 - 30% black
- .text-faded-20 - 20% black
- .text-faded-10 - 10% black

### White Fade (white alpha from 90% to 10%)

- .text-faded-inverse-90 - 90% white
- .text-faded-inverse-80 - 80% white
- .text-faded-inverse-70 - 70% white
- .text-faded-inverse-60 - 60% white
- .text-faded-inverse-50 - 50% white
- .text-faded-inverse-40 - 40% white
- .text-faded-inverse-30 - 30% white
- .text-faded-inverse-20 - 20% white
- .text-faded-inverse-10 - 10% white

## Spacer

Spacer is top-margin that can be added to an element. Spacer will default to the spacer-md size.

```
<div class="spacer spacer-sm">
	I'll have a little margin on the top.
</div>
<div class="spacer">
	I'll have some more margin on the top.
</div>
<div class="spacer spacer-xl">
	I'll have event more margin on the top.
</div>
```
### Spacer add ons

- **spacer-off**  
- **spacer-sm**
- **spacer-md**
- **spacer-lg**
- **spacer-xl**

#Todo:

- Add adjustments for media queries
