jQuery UI Combobox 1.0.0
=========================
 
 Copyright 2011, Eric Mann and Jumping Duck Media (http://jumping-duck.com)
 Dual licensed under the MIT or GPL Version 2 (or later) licenses.
 
 Depends on:
 
 - jquery.ui.core.js
 - jquery.ui.widget.js
 - jquery.ui.position.js
 - jquery.ui.autocomplete.js

 This plugin is based on the combobox example of the jQuery UI Autocomplete widget.
 
 It will convert any standard select field into a combobox field (an input element paired with a dropdown element).
 
 Users can then either select a field from the underlying dropdown or input text directly.  The element will attempt to automatically match the user's input with one of the select's options.  If no appropriate option is found, the user can leave their manually entered text.
 
 Example use:
 =======================
 
 ```
 <select id="combobox">
     <option value="">Select an option...</option>
	 <option value="1">One</option>
	 <option value="2">Two</option>
	 <option value="3">Three</option>
 </select>
 
 <script type="text/javascript">
     $( "#combobox" ).combobox();
</script>
```