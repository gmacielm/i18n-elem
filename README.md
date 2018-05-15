# \<i18n-elem\>

 This element switch the language of a html text.

## For view demo of component execute
```
$ polymer serve
```
and go to this url: localhost:8081/components/i18n-elem/demo/

## Foe Running Tests

```
$ polymer test
```

## Usage

```html
<i18n-elem selectedItem="[[lang]]" selectedUrl="[[url]]"></i18n-elem>
```
The language can be modified by a dropdown button or normal buttons that changes the lang
properties, if the langs does not exist will be appear a modal with the error.

We must to put our json database with our langs on an folder and save our json documents.
the url must be have this formar:

foldeUrl/fordeName/langCode.json

the folder struc should be so:

**FolderName as a root**

| languaje        | document           | iso  |
| ------------- |:-------------:| -----:|
| Spanish      | es.json | 639-1 |
| English      | en.json | 639-1 |
| French | fr.json | 639-1 |

[for motre info view iso-639-1](https://es.wikipedia.org/wiki/ISO_639-1)

## Properties

selectedItem is a String, default is 'es'
selectedUrl is a String, does not have default value


## History

The globalization require the apps can deploy in diferents languages,
thinking in this ploblem we create this component.

## Credits

@hectorcaire
@davidhdzhdz
@gmacielm

## License

MIT License
