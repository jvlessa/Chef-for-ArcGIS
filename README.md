# Chef Client for ArcGIS

## Installation
- Download Chef Client [(Windows .MSI)](https://downloads.chef.io/chef/14.5.33#windows);
- Install it (no need of fancy configurations);
- Notice that the setup created a folder called <b>"chef"</b> on C drive;
- Open Power Shell or Command Line and check if the command <b>"chef"</b> is working;
- If it's not, you must puth the folder "bin" and "embedded" from the installation directory on Windows PATH Variable;

## Creating Cookbook
- The command: ```knife cookbook create cookbookname``` was removed from new versions. 
- Now we need to download the ChefDK [(.Msi File)](https://packages.chef.io/files/stable/chefdk/3.3.23/windows/2012r2/chefdk-3.3.23-1-x64.msi);
- Install it (no need of fancy configurations);
- After installation, go to the folder <b>C:/chef</b> and create one called <b>"cookbooks"</b>;
- Inside the cookbook folder, run the command: ```chef generate cookbook cookbookname```;

## Editing Recipe
- Edit the file inside the folder recipes, called: <b>"default.rb"</b>;

## Schema 
- Cookbooks ==> Recipes ==> Roles

## Runner 
Run the command: ```chef-solo --override-runlist "recipe[joao::default]"```

## Possible Errors 
#### chef-client doesn't have administrator privileges on node MACHINENAME
- Run as Administrator

## Links 
[Chef Client Download](https://downloads.chef.io/chef/14.5.33#windows)

[Tutorials](https://learn.chef.io/tracks/infrastructure-automation/)

[Esri Cookbook](https://github.com/Esri/arcgis-cookbook)
