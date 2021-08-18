# Toddler Social Words API 

A minimal API I created to get access to specific words as well as the pictures and audio associated with them.

This was created for my baby-socrates client app. I wanted to make sure the images and audio coming back were exactly the ones I wanted—at least for the social words game.

### MP3

MP3 are stored in Google Drive. 

Currently(as of 2021) to access the mp3 the url would be: `https://drive.google.com/file/d/[ID_HERE]/view?usp=sharing`.

For a direct link to the URL: `http://docs.google.com/uc?export=open&id=[ID_HERE]`. 

Where `[ID_HERE]` should be replaced by the id of the mp3. 

Since the Google URL might change and most likely the id will stay the same, I have stored only the id as `storeId` and not the full url. The full url can be setup/changed in the client app.