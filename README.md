#Bootstrap spacing

The missing white space needed for a consistent bootstrap experience.

##Spacer

Spacer is a margin that can be added to any element. By default spacer adds margin only to the top. Spacer defaults to the spacer-md.

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
###Spacer add ons

- **spacer-off**  
- **spacer-sm**
- **spacer-md** 
- **spacer-lg**
- **spacer-xl**

##Padding

Like spacer, padding can be added to any element, but this time it's padding.

```
<div class="row">
	<div class="col-sm-3 ">
		<div class="spacer spacer-lg spacer-bottom hairline hairline-top hairline-bottom padding padding-sm padding-top-bottom">
			hairline hairline-top hairline-bottom padding padding-sm padding-top-bottom
		</div>
	</div>
	<div class="col-sm-3 ">
		<div class="spacer spacer-lg spacer-bottom hairline hairline-top hairline-bottom padding padding-lg padding-top-bottom">
			hairline hairline-top hairline-bottom padding padding-lg padding-top-bottom
		</div>
	</div>
	<div class="col-sm-3 ">
		<div class="spacer spacer-lg spacer-bottom hairline hairline-top hairline-bottom padding padding-xl padding-top-bottom">
			hairline hairline-top hairline-bottom padding padding-xl padding-top-bottom
		</div>
	</div>
	<div class="col-sm-3 ">
		<div class="spacer spacer-lg spacer-bottom hairline hairline-left hairline-right padding padding-md-bottom padding-md padding-xl-top">
			spacer spacer-lg spacer-bottom hairline hairline-left hairline-right padding padding-md-bottom padding-md padding-xl-top
		</div>
	</div>
</div>
```

![](http://snap.icorbin.com/Screen-Shot-2015-07-27-17-25-20.png)

###Padding add ons

- **padding-off-top**  
- **padding-sm-top**
- **padding-md-top**
- **padding-lg-top**
- **padding-xl-top**


- **padding-off-bottom**  
- **padding-sm-bottom**
- **padding-md-bottom**
- **padding-lg-bottom**
- **padding-xl-bottom**


- **padding-off-left**  
- **padding-sm-left**
- **padding-md-left**
- **padding-lg-left**
- **padding-xl-left**


- **padding-off-right**  
- **padding-sm-right**
- **padding-md-right**
- **padding-lg-right**
- **padding-xl-right**

##Hairline

Hairline is a 1px 20% black border. You can apply it to the top, bottom, left, or right of an element.

```
<div class="spacer padding hairline hairline-top">
	I'll have a some more padding on the top some margin AND a border
</div>
```

###Hairline add ons

- **hairline-top**
- **hairline-bottom**
- **hairline-left**
- **hairline-right**

#Todo:

- Add adjustments for media queries
