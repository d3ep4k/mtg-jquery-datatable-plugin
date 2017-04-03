# mtg-jquery-datatable-plugin
This plugin can be directly used to render the JSON response received from a Metamug Backend API into jquery datatable.
```
$(document).ready(function(){

	$(this).mtgDataTable('#datatable', 'https://api.metamug.com/dtable/v1.0/employee');
	
});
```
