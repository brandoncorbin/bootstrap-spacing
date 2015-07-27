#Bootstrap spacing

The missing white space needed for a consistent bootstrap experience.

##Spacer

Spacer is a margin that can be added to any element. By default spacer adds margin only to the top. Spacer defaults to the spacer-md.

```
<div class="spacer spacer-sm">
	I'll have a little margin on the top.
</div>
<div class="spacer">
	I'll have a some more margin on the top.
</div>
<div class="spacer spacer-xl">
	I'll have a some more margin on the top.
</div>
```


##Padding

Like spacer, padding can be added to any element, but this time it's padding.

```
<div class="padding padding-sm">
	I'll have a little padding on the top.
</div>
<div class="padding padding-md">
	I'll have a some more padding on the top.
</div>
<div class="padding padding-xl">
	I'll have a some more padding on the top.
</div>
```

###Padding add ons

- **padding-top-bottom**
- **padding-left-right**

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
