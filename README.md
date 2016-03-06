# fullscreen-enabled
   
This behavior teaches elements how to use the Fullscreen API.

Check out the [component page](http://l-u-k-e.github.io/fullscreen-enabled/components/fullscreen-enabled/) for the API docs and a demo.

**This behavior requires that an instance of lodash be instantiated in the global scope prior to its instantiation.**

### Install with Bower

    bower install --save L-u-k-e/fullscreen-enabled

### Use it in your element

This behavior is added to the `Behaviors` namespace. 
    
    <script>
      Polymer({
        is: 'video-player',
        behaviors: [Behaviors.fullscreen_enabled],
        ...
      });
    </script>

Once you've mixed the behavior into your element, toggling full screen is as simple as toggling the `fullscreen` property.
   
   
