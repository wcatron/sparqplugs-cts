sparqplugs-cts
==============

SPARQL Environment config and plugins for the CTS project. 

## Installation and Setup

Follow standard SparqPlug installation proccess.

**Extra config information** is needed. You must an array of your initial element types to the config file.

```
	"cts":{
		"types": {
			"Editions":"cts:Edition",
			"Collections":"cite:CiteCollection",
			"Works":"cts:Work",
			"Text Groups":"cts:TextGroup",
			"Translations": "cts:Translation",
			"Image Collections": "cite:ImageArchive"
		}
	}
```

## Plugins

#### *in.cts.*Browser

Adds a nice interface to your CTS project. Quickly get up and running querying the dataset for specific words across any of your elements. Great for inexperienced programmers to be able to search for words and by using other plugins, analyse their results without programming anything.

**Features**

- Browse your element types.
- Search through properties of these types using RegEx.
- Great for searching for words and clusters of words.
