# Call of Duty 4 Maps


## JSON

### Pathing
This area describes where to load the .iwd, _load.ff and .ff file on your local machine using a mac. When the user receives the following files these are the 3 common files to play custom multiplayer maps for Call of Duty 4 in order to use the COD4 command line:

**localized_english_mp_name_of_map.iwd =** /Applications/Games/Call of Duty 4/Call of Duty 4 Data/main

The 2 files below are to be added to the same location:<br />
**mp_name_of_map_load.ff =** /Applications/Games/Call of Duty 4/Call of Duty 4 Data/zone/english<br />
**mp_name_of_map.ff =** /Applications/Games/Call of Duty 4/Call of Duty 4 Data/zone/english

### Definition
**name =** The name of file to run using the COD4 command line<br />
**rating =** How awesome or good the map is<br />
**game-type =** What the map supports during game time<br />
**map-size =** file size of what you will be downloading to your local machine<br />
**map-screenshot =** preview of the map you are about to play<br />
**iwd-github-path =** file path within github to get to this file<br />
**loadscreen-github-path =** file path within github to get to this file<br />
**map-github-file =** file path within github to get to this file

### Example
<pre><code>{<br />
  "name": "mp_name_of_map",<br />
  "rating": "7/10",<br />
  "game-type": "DM, TDM, SD, HQ, DOM, SAB",<br />
  "map-size": "58.7 MB",<br />
  "map-screenshot": "/maps/mp_name_of_map/mp_name_of_map.jpg",<br />
  "iwd-github-path": "/maps/mp_name_of_map/localized_english_mp_name_of_map.iwd",<br />
  "loadscreen-github-path": "/maps/mp_name_of_map/mp_name_of_map_load.ff",<br />
  "map-github-file": "/maps/mp_name_of_map/mp_name_of_map.ff"<br />
}</code></pre>