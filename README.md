#Bootstrap spacing

The missing white space needed for a consistent bootstrap experience.

You followed the Boostrap way, and yet, things still look funny all bunched together? So you start figure investigating why. You add a row here, a col-xs-12 there and finally you get it look "close enough". But you've just created an unmanageable nightmare.

Let's stop the madness, bootstrap-spacing is designed to give you the padding and margin control you need without a bunch of divs, .rows and .col-whatever-12.

##Spacer

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


##Margin

Just like padding, but for margin. Requires "margin" to be included in the class name - e.g. `class="margin margin-xl-top"`

```
<div class="margin margin-md"></div>
```

###margin add ons

- **margin-off-top**  
- **margin-sm-top**
- **margin-md-top**
- **margin-lg-top**
- **margin-xl-top**
- **margin-off-bottom**  
- **margin-sm-bottom**
- **margin-md-bottom**
- **margin-lg-bottom**
- **margin-xl-bottom**
- **margin-off-left**  
- **margin-sm-left**
- **margin-md-left**
- **margin-lg-left**
- **margin-xl-left**
- **margin-off-right**  
- **margin-sm-right**
- **margin-md-right**
- **margin-lg-right**
- **margin-xl-right**

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
