# Lexer and Parser for Z

## Implementation decisions
* In the Z specification language, top was defined in seq/dict but was not mentioned whether or not it could be used as a normal assignment (e.g. top a = 5;), so we assumed that it was possible to assign as a top type.

## Building
To build, issue `make`.


## Testing
To test, issue `make test`.

## Credits
* Alex Xu
* Galen Han
* Jamie Law