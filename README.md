#jQuery Hotkeys

Library allows you implement key shortcuts behaviour with jquery. Sometimes there is needed to implement for example help guide on page when application has many features and functions. The simplest way is to add icon on page and of course add shortcut "f1" for displaying help guide.

 ````html
<script src="/jquery/jquery.js"></script>
<script src="/jquery-hotkeys/jquery-hotkeys.js"></script>
 ````

 ````javascript
$(document).hotkey('ctrl+c', function() {});
$(document).hotkey('ctrl+alt', function() {});
$(document).hotkey('enter+f1', function() {});
````

