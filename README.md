# OneDrive PHP Client for public folders and files

I've written this little app/library because I wanted to use a public folder on OneDrive as a CDN. Getting embed URLs from the OneDive GUI can be quite painful.

To do this programatically, I  needed a way to traverse and get the file download URLs for all OneDrive files in a public folder.

This will do just that using the OneDrive API.

To see how it works, have a look at get.php. Simply replace the URL for the short link there with the shortlink for your public OneDrive folder and off you go.

I simply write the output to a JSON file and push it to the server and use the URLs there. You can write the URLs of your folder to a JSON file with:

```
php get.php > /path/to/file.json
```

Backgrounds.json is an example of what this produces.

More info coming soon. Right now this is just functional enough for what I need.
