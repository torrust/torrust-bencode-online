# Torrust Bencode Online

A web application to convert from Bencode format to JSON format and vice versa.

It's a clone of this project: <https://github.com/Chocobo1/bencode_online> with a few changes.

## Features

- It uses the Torrust crates [bencode2json](https://github.com/torrust/bencode2json) and [json2bencode](https://github.com/torrust/json2bencode) for the conversion.
- The conversion is done on the client side.
- It compiles Torrust the crates to WebAssembly, exposing the Bencode-to-JSON conversion functions.
