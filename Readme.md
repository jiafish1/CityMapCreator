# True Location CityMap Creator

## Tool for creating true location city map code

To generate true location for cities, a CityMap.xml is used under the YnAMP mod. However, generating such a file and assigning each block while switching back and forth is a painful process. This tool aims to make that process easier. 
![Map view](/display/tooldisplay3.png)
This tool is just a html page that loads up an image that you have placed in the same folder. It creates outlines around each block with input in each block.
You can enter the city you want for each block in the input field and leave it there. It will be saved automatically.

After you have finished naming everything, click the export to xml button at the bottom of the page, and it will save an xml file with the code needed in CityMap.xml.
![Map view](/display/tooldisplay4.png)
You can also load existing xml or json to work with other people simultaneously. Just paste the code in the textbox under the corresponding buttons and click import.

Feel free to customize the map. Open up the html file and you will see under the `<script>` section, some constant parameters. You can change the size for the map width, height, the map name used in the xml code, etc.

To replace with your own map, take a screenshot of the entire map, save the image to the same folder. Open the html, search for `background-image` and change it to the name of your image.

Change the `MAP_WIDTH` and `MAP_HEIGHT` to your map's in-game width and height.

Change the `top_bar` div's height, `BLOCK_HEIGHT`, and `BLOCK_WIDTH` to align the red squares to the blocks on your map, then work away.
