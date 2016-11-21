# Joseph plays with Text to Speech.
The first effort is a python script that makes a call to the Google TTS API, taking in a text string and outputting an mp3 of the string spoken in synthetic speech. The only parameter available in this interface is language, which is surprisingly fun to play with. Unsurprisingly, the speech sounds better when the text is of the language of the speech synthesis. But it can be fun to try to make the French or Czech speech synthesizers speak English, for example.

An example of English TTS of string "The frenetic agent was speaking crazily with Bon Jovi.":
https://drive.google.com/open?id=0B_f2DXqYwl14SE5MVV8wRmIycWc

The same sentence produced with the Czech synthesizer:

https://drive.google.com/open?id=0B_f2DXqYwl14ODNzd0pPWTVTR0k

I made a madlib style game to generate sentences.

Supported Languages:

* 'af' : 'Afrikaans'
* 'sq' : 'Albanian'
* 'ar' : 'Arabic'
* 'hy' : 'Armenian'
* 'bn' : 'Bengali'
* 'ca' : 'Catalan'
* 'zh' : 'Chinese'
* 'zh-cn' : 'Chinese (Mandarin/China)'
* 'zh-tw' : 'Chinese (Mandarin/Taiwan)'
* 'zh-yue' : 'Chinese (Cantonese)'
* 'hr' : 'Croatian'
* 'cs' : 'Czech'
* 'da' : 'Danish'
* 'nl' : 'Dutch'
* 'en' : 'English'
* 'en-au' : 'English (Australia)'
* 'en-uk' : 'English (United Kingdom)'
* 'en-us' : 'English (United States)'
* 'eo' : 'Esperanto'
* 'fi' : 'Finnish'
* 'fr' : 'French'
* 'de' : 'German'
* 'el' : 'Greek'
* 'hi' : 'Hindi'
* 'hu' : 'Hungarian'
* 'is' : 'Icelandic'
* 'id' : 'Indonesian'
* 'it' : 'Italian'
* 'ja' : 'Japanese'
* 'ko' : 'Korean'
* 'la' : 'Latin'
* 'lv' : 'Latvian'
* 'mk' : 'Macedonian'
* 'no' : 'Norwegian'
* 'pl' : 'Polish'
* 'pt' : 'Portuguese'
* 'pt-br' : 'Portuguese (Brazil)'
* 'ro' : 'Romanian'
* 'ru' : 'Russian'
* 'sr' : 'Serbian'
* 'sk' : 'Slovak'
* 'es' : 'Spanish'
* 'es-es' : 'Spanish (Spain)'
* 'es-us' : 'Spanish (United States)'
* 'sw' : 'Swahili'
* 'sv' : 'Swedish'
* 'ta' : 'Tamil'
* 'th' : 'Thai'
* 'tr' : 'Turkish'
* 'vi' : 'Vietnamese'
* 'cy' : 'Welsh'
