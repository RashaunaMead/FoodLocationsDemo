##CartoDB

A quick first pass at using CartoDB with google doc for Farm Map

Data: [USDA](http://catalog.data.gov/dataset/farmers-markets-geographic-data)

## CartoDB workflow

[link to example map](http://rashaunamead.github.io/FoodLocationsDemo/cartoDBTest.html)

2. Used Google sheets
3. uploaded to cartoDB
4. make GEOM column (find documentation)
5. Edited it with UI
6. Export api link
7. Frame work code from cartoDB
8. Custom SQL calls with UI



http://docs.cartodb.com/cartodb-editor.html


Update: 
1. Export data view
2. Load into drive sheets
3. update sheets with new info
4. Go back to cartoDB delete table
5. upload table from drive
6. Restore map

Update steps would not be neccesary if we were using the "john snow" plan

Easy to make: Very
Easy to edit without code: Yes
Easy to update: not really without paid plan
Geocoding: not great

## Google Maps API

[link to example map](http://rashaunamead.github.io/FoodLocationsDemo/googleTest.html)

1. Make fusion table
2. Georeference table
3. Share / capture table key
4. get an api key
5. insert keys into html to use table and api
6. Custom SQL calls with UI

[API](https://developers.google.com/maps/documentation/javascript/reference)

[infowindow](https://developers.google.com/fusiontables/docs/samples/change_infowindow_content)

Easy to make: not really
Easy to update without code: nope
Easy to update: should be
Geocoding: works great with x,y coords


http://mapschool.io/