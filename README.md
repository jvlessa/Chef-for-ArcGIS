# Chef Client for ArcGIS

## Installation
- Download Chef Client [(Windows .MSI)](https://downloads.chef.io/chef/14.5.33#windows);
- Install it (no need of fancy configurations);
- Notice that the setup created a folder called <b>"chef"</b> on C drive;
- Open Power Shell or Command Line and check if the command <b>"chef"</b> is working;
- If it's not, you must puth the folder "bin" and "embedded" from the installation directory on Windows PATH Variable;

## Creating Recipe
The command: ```knife cookbook create cookbookname``` was removed. Than, we need to download the ChefDK and run another one;
1. ```curl -s https://omnitruck.chef.io/install.sh |bash -s -- -P chefdk```

## Schema 
- Cookbooks ==> Recipes ==> Roles

## Links 
[Chef Client Download](https://downloads.chef.io/chef/14.5.33#windows)

[Tutorials](https://learn.chef.io/tracks/infrastructure-automation/)

[Esri Cookbook](https://github.com/Esri/arcgis-cookbook)
