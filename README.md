Has it ever occured to you that you were reading an old bookmark or some lengthy blog post and suddenly realized you had read it already before? It would be fairly easy to search in chrome history, however it is only stored locally for three months. 

Or perhaps you even have a habit of annotating and making notes elsewhere? And you wanna know quickly if you have the current page annotated. Then this tool is for you.

The Chrome extension consumes a JSON file with history. It may be generated from:

* local sqlite history database backups
* Google Takeout/Activity backups
* or anything else with a simple script. It's JSON, duh!

# Configuring
* generator: TODO `cp config.py.example config.py`, edit config.py, run `python3 -m wereyouhere`
* extension: choose the generated JSON in the extension settings

# TODOs
* commit scripts to process history sources
* collect from filesystem
* [in progress] use chrome history too
* [in progress] be more informative; show full history or at least last visit and potentially sources (e.g. hypothesis)
** maybe icons for mobile/desktop?
* use some sort of smarter matching, e.g. no difference between http and https
* ignore some schemas/urls
