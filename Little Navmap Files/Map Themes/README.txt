These are a set of Google and other aeronautical map 'themes' originally provided by Victor 'bina' Quebec using public assets and modified by the developer of LittleNavMap, Alexander Barthel. Full credit goes to their work for providing these wonderful additions to LNM.

The Google maps included in this package fix issues with map labels which appear in random languages.

NOTE*** Installation of Map Themes has been updated. Installation instructions are provided below for first-time users of this package and those who already have the package installed. The following steps should keep things fairly simple.

*First-Time users of this package -

First, you need to prepare LNM to use additional map themes. You need to create a folder to put your additional map themes into. You can name and place the folder as desired (example: D:\Little Navmap\Map Themes). In this example the Map Themes folder is actually placed in the Little Navmap folder though placing the folder outside the LNM folder is recommended (see note 2 below).

Next, start LNM and select 'Tools' -> 'Options' -> 'Cache and Files' (located near the bottom left of the window). Find 'Directory for Additional Map Themes' on the right side of the window and click on 'Select Themes Directory...' and navigate to the folder just created and select it (again, as in the above example: D:\Little Navmap\Map Themes).

Now clear the existing map cache. You can open the map cache folder by selecting 'Tools' -> 'Files and Directories' -> 'Show Map Cache'. Remove all google-... folders there.

Finally, drop all the folders contained in this package into the folder you created and skip down to the 'Final Step' below.

*Users with this package already installed -

Go to the folder where you previously installed the map themes from this package (example: D:\Little Navmap\Data\Maps\Earth). This is the folder where the default map themes (those included with LNM) are located. Highlight each of the folders installed from this package and 'Cut' them so you can move and paste them to the newly created folder as described for first-time users above. It is important to move all addon map themes other than the default themes installed with LNM to the newly created folder. 

List of map themes contained in this package:

finland-topo
goggle-maps-def
goggle-maps-sat
goggle-maps-ter
norway-topo
sweden-topo


*Final Step -

RESTART LNM!

After restarting LNM check to ensure everything turned out okay by clicking on the icon that resembles the Earth on the menu bar and select the map theme you wish to use.

After installing the maps and clearing the cache (first-time users) all labels should show in your local language which is set in the LNM options on the "User Interface" page.

Note 1: Be aware some of the new maps are not global in nature, for example, the Enroute Low/High charts for the USA cover only those applicable areas across the USA (not globally). Remaining areas will provide only a blank display in the moving map for other areas on the globe. The topograpical maps for Norway, Finland, and Sweden work the same way (only for those specific areas). The Google maps are global maps.

Note 2: Keep in mind if you have placed the map themes folder inside the LNM application folder (as in the above example) you must temporarily move it outside the LNM folder before deleting the old LNM version to install a new version since there is the danger of accidentally deleting the map themes during the update. Hence, it is highly recommended to place the folder outside the application folder.

Note 3: Always be on the lookout. Though hard to find, map themes can be found which are compatible with LNM and provide different type overlays such as aeronautical maps or street maps and others. Further, different maps come with different types of symbology which will have their own map legends. These legends are typically available from the theme provider. Some map themes installed with LNM have map legends you can access in the menu bar.

Note 4: As mentioned Little Navmap by default comes with several map overlays but maps provided in this package come from third parties, such as Mapbox.com, Thunderforest.com, and Maptiler.com. To use their maps you need to create an account with them and obtain an API key, sometimes referred to as a token. The key allows you to download their content for use in LNM. Typically there is no cost for a free account (used for hobbies and such) but may have limits applied to the data used (reference each site for more information). Once a key is obtained go here in LNM (Tools>Options>Map Display Keys) to enter the keys. The LNM developer has allocated fields for you to enter the keys for each. Afterwards, when that map theme is selected in Little Navmap the map overlay will properly display. Be aware Mapbox User is for custom map overlays you can create at the Mapbox.com website. Reference their site for more information.

Note 5: Additional details about LNM Map Themes, including installation examples can be found at the LNM website link below:

https://www.littlenavmap.org/manuals/littlenavmap/release/latest/en/MAPTHEMES.html#installing-map-themes

Version Change Log:

Version 1.1 -	Included note #4 about API keys.

Version 1.2 -	Rewrote new install instructions into README.

Version 1.3 -	Fixed the .DGML files to correct zooming in map themes.

Version 1.4 -	Removed outdated (non-working) 'chartbundle' map themes. 
		
		us-helicopter
		us-ifr-area
		us-ifr-high
		us-ifr-low
		us-tac
		us-vfr-sectionals

		These are no longer supported by the original creator. Sorry if 		anyone downloaded this package prior to this new posting as I 		didn't find out about this until recently. Alexander Barthel 		has indicated a new map theme 'Stadia StamenTerrain' will be 		introduced in an upcoming version of LNM which will require an 		API key as described in note #4 above.


Enjoy,

NCHawk5018