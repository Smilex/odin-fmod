# odin-fmod
WIP Odin bindings for [FMOD](https://www.fmod.com/).

Current version: `2.02.15`

Includes `core`, `fsbank` and `studio` APIs. The `dll` and `lib` files are downloaded from https://www.fmod.com/download.

[FMOD API documentation](https://www.fmod.com/docs/2.00/api/welcome.html)

## Example
You can see example usage in [example.odin](example/example.odin). Runs on raylib.

Run with:
```cmd
cd example
odin run .
```

## TODO
- Add more examples
- Translate constants to enums and bit_sets.
- Implement odin wrappers for common procedures, to allow usage of slices and maybe allocators.

## Contributing
All contributions are welcome, I will try to merge them when I can!
