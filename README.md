# twemoji_xpm

Experiments in conversion to xpm of twitter's emojis for a tiny OLED. These didn;t work but might come in handy for something anyway?

These are versions of twitter's emojis: https://github.com/twitter/twemoji

Conversion script: 

    cp -r 72x72 48x48xpm
    mogrify -threshold 50% -resize 48x48 -format xpm *.png


