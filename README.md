# Toddler Social Words API 

A minimal API I created to get access to specific words as well as the pictures and audio associated with them.

This was created for my toddler-9000 client app. I wanted to make sure the images and audio coming back were exactly the ones I wanted—at least for the social words game.

## See it Live [here](https://toddler-social-words-api.herokuapp.com/).
### Notes

Data is stored in Google Drive. 

To access a Google Drive url(as of 2021): `https://drive.google.com/file/d/[ID_HERE]/view?usp=sharing`.

For a direct link to the URL: `http://docs.google.com/uc?export=open&id=[ID_HERE]`. 

Where `[ID_HERE]` should be replaced by the id of the audio/image. 

Since the Google URL might change and most likely the id will stay the same, I have stored only the id and not the full url. The full url can be setup/changed in the client app.