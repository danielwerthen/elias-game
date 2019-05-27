# Html + JS environment

To do development, simply edit the files `index.html` and `src/index.js`. To test it in the browser, one of many ways, is to use httpserver in python

```bash
cd dir/with/this/README
python3 -m http.server
```

Then you can use a web browser to navigate to `http://localhost:8000`. Http.server serves all the files in the directory, so if you create a new file called `daniel.html` you can navigate to with `http://localhost:8000/daniel.html`.

For an improved dev experience you want to consider using a server that automatically reload the browser when you SAVE changes to the files. There is a lib in python called HttpWatcher, but again, there are many tools like. HttpWatcher can be used like this:

```bash
pip install httpwatcher
httpwatcher
```

This command, `httpwatcher` will also open a web browser with the correct url for you!

