<h3>1_Data Cleaning :</h3>
Suppr the merged columns of the first line<br>
Replace  0 by - <br>
Relace N/A by 0 <br>
Save as rex2013.csv <br>

<h3>2_CartoDB:</h3>
Connect to Cartodb <br>
Drag'n drop rex2013.csv <br>
Make the table public <br>
Go to the rex2013 table and change format of certain field according to the data dictionay in the excel table <br>
Go to Visualisation and create region2013 with 2 layers : rex2013 and rexregion84 (delegation coverage)  <br>
Make sure number 1 is rexregion84 and number 2 is rex2013 <br>
Make all fileds avaialable in the infowindows of rex2013 and rexrefion84 layers  <br>

<h3>3_In each of th 9 html page:</h3>
Change 2012 to 2013 <br>
Replace the .viz from region2013 by the one for regions2013 visualisation <br>
Replace rex2012 in sql query to rex2013 <br>
Replace #rex2012 in the cartocss to #rex2013 <br>

