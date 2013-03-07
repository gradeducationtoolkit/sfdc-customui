Custom UI Components
=====================

This is collection of UI Components

## Collections

- Bootstrap
    bootstrap component which can be used inside visualforce page and keep the SFDC standard stylesheet intact. 
    More information about customized bootstrap [here] (http://smulyono.github.com/sfdc-bootsrap)

- Chosen
    Using chosen library to change the combobox looks better. Including the component will automatically replace standard salesforce
    multi combobox with chosen.

## How to Use

* Upload this [component / unmanaged package] (https://login.salesforce.com/packaging/installPackage.apexp?p0=04tE0000000UoKI) into your SFDC Orgs
* Use the components inside the visualforce page

```
<apex:page>

<!-- put / drop it to the page -->
<c:bootstrapcomponent />
<c:chosencomp />
<script type="text/javascript">
// to use javascript with bootstrap
$j_bootstrap(document).ready(function(){

});

// to use javascript with chosen
$j_chosen(document).ready(function(){


});
</script>
</apex>

```

