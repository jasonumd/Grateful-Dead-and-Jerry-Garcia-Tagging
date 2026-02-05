# **NOTE: THIS REPOSITORY IS OUT OF DATE
I'm keeping it here because it could still be useful to someone initiating the tagging of a large Grateful Dead and/or Jerry Garcia library. Refer to Live-Music-Tagging repository instead.

# **Grateful Dead and Jerry Garcia**
Digitizing Grateful Dead data and making it freely available to all Deadheads.

## **music_album_rename**
This script uses a database from JerryBase.com to set the album and artist/albumartist of an entire Grateful Dead and Jerry Garcia library based on the date in the show folder name.  The folder must start with either "gd" or "jg" and the date must be in YYYY-MM-DD format. The album format is "YYYY-MM-DD (sbd/aud/fm/tv/fob/studio/gmb/pa/mtx [Miller] [shnid]) [(Early/Late Show)] Venue, City, State". The database is courtesy of the database admin for JerryBase.com and it contains all information for Grateful Dead and Jerry Garcia shows. Obtaining an export of this database was a lifesaver, especially for tagging Jerry Garcia shows.

## **song_exist
This is a simple script to scan a folder to see if the song title exists in the database. Useful for checking for typos, etc.

## **song_title_get
This script creates a delimited file of paths and song titles.

## **song_title_set
This script sets song titles based on the previously mentioned delimited fie.