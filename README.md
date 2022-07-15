# bbw-mock-data
Blue Billywig mock-data for Figma.

# How to use
- Install the Mock plugin: https://www.figma.com/community/plugin/908371597321736295/Mock
- Click on Edit lists
- Add the following URL: https://raw.githubusercontent.com/tomkle/bbw-mock-data/main/index.json

# Add additional mock data
You can add additional mock data by editing the `index.json` file.

Add a new category to the bottom of the lists section:

``` json
,{
  "name": "Name of new category",
  "path": "new-category.txt"
}
```
Then create the `new-category.txt` file in this repo and start adding your input. Each (new)line is a unique entry.

``` txt
First entry
Second entry
Third entry
etcetera
```
