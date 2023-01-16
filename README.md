# minetranslate
Python script to automatically create Google Translated language files for Minecraft

## Installation
1. Make sure you have Python 3 and pip installed
2. Install dependencies: `pip install googletrans==4.0.0rc1`
3. Run the script

## Usage
```
$ ./minetranslate 
usage: minetranslate [-h] json_file dest_lang
```
#### Example: 
##### To translate es_es.json (Spanish language file obtained from Minecraft assets folder) to English: 
`./minetranslate es_es.json en`
