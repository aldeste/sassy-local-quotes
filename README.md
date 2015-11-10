# Sassy local quotes
Easily get the correct quotes used in your supported languages.

## Installation

@include the local-quotes file.

## Usage
```
// SCSS
$languages: ('en', 'it-IT', 'es-ES');
```
This will output the following CSS
```
:lang(en) q,
:lang(en) blockquote {
  quotes: '“' '”' '‘' '’';
}

:lang(it-IT) q,
:lang(it-IT) blockquote, :lang(es-ES) q,
:lang(es-ES) blockquote {
  quotes: '«' '»' '“' '”';
}
```

Have fun.
