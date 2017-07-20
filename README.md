# Tablamo!

## Description
A Sinatra app that uses the [MusixMatch API](https://developer.musixmatch.com/) to fetch lyrics. Users can then use the lyrics to generate their own guitar or ukulele tabs.

### Details
* Employs the MVC model.
* Makes use of the MusixMatch API.
* ___Database___: PostgreSQL  
* ___Dependencies___: HttParty

## Functionality

### Fetching Lyrics
Users simply have to enter an artist name and song, and hit 'Get Lyrics'! The application fetches and parses the lyrics, then generates a form. | 
------------------------------ | 
![Fetching Lyrics](https://github.com/pnewsam/tablamo/blob/master/readme_assets/fetching_lyrics.gif "Fetching Lyrics") |

### Creating Tabs
After filling out the form, the user simply hits 'Create Tab', and ___tablamo!___ The tab gets saved and added to the list on the homepage.|
------------------------------ | 
![Filling in Chords](https://github.com/pnewsam/tablamo/blob/master/readme_assets/filling_in_chords.gif "Filling in Chords") |
![Generating Tab](https://github.com/pnewsam/tablamo/blob/master/readme_assets/generating_tab.gif "Generating Tab") |