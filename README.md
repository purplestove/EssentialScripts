# Stove random scripts
yes


# MsFinder V2
⚠️Will make a better version someday, using packet to talk with scarpet and analyse what's in chests, instead of using any sort of database to save items locations⚠️


The point is to highlight location/chest containing a wanted item.
Those itemsLocations are stored in `MsLayout.csv`\
In _SinglePLayer_ you are able to use commands that edit the csv file such as `addLocationFor` to add a location for an item or `removeLocationFor` to remove a location for an item.\
Those commands are unusable in _MultiPlayer_.

## Configs
First you need to set a keybind to open MsFinder config screen.
![image](https://user-images.githubusercontent.com/41466968/171277168-2521f8dd-8738-4385-b28d-13a83693e4c1.png)

On the config screen you can edit 3 differents rules.
![image](https://user-images.githubusercontent.com/41466968/171277056-a5ed0d45-e79f-4405-b659-4b7b7981cb30.png)

`Auto-Update csv` : Set to `true` if you want to download the csv file each times you connect to a server in `Auto-Update server list`\
`Auto-Update server list` : A list of `server address` on which you want to auto update the csv file when you log on\
`Csv download url` : Typically a _Google Spreadsheet_ url -> `https://docs.google.com/spreadsheets/d/<SPREADSHEET_URL>/export?format=csv&gid=<SHEET_ID>`\
- Remove `&gid=<SHEET_ID>` if your Spreadsheet is only 1 sheet
- `export?format=csv` is the important part to ba able to download the file as a csv
