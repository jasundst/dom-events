# dom-events

Binds Dom Events to actions on Highcharts elements.

This fork was created to reduce the doubleclick wait delay.

### Usage

Add event handler as any other event handler in Highcharts:
```javascript
events: {
    contextmenu: function(e) {
        ...
    }
}
```

### Supported events per element

Events       | Plot Area | Series | Point
------------ | --------- | ------ | -----
dblclick     | -         | -      | - 
mousedown    | -         | -      | - 
mouseup  	 | -         | -      | - 
mousemove 	 | -         | -      | - 
mouseout	 | -         | -      | - 
mouseenter 	 | -         | -      | - 
mouseleave	 | -         | -      | - 
wheel		 | +         | -      | - 
contextmenu	 | +         | +      | + 
