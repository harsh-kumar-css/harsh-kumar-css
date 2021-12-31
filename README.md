

[layer setShadowOffset:CGSizeMake(0, 3)];
[layer setShadowOpacity:0.4];
[layer setShadowRadius:3.0f];
[layer setShouldRasterize:YES];

[layer setCornerRadius:12.0f];
[layer setShadowPath: [[UIBezierPath bezierPathWithRoundedRect:[self bounds]cornerRadius:12.0f] CGPath]];
<kbd>
<img align="center" src="https://i.pinimg.com/originals/a5/35/60/a53560c8088900e266880f779dacced7.gif" width="400"/>
</kbd>
