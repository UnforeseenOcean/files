# RigEK's Binary Decoder
This program decodes the malware's encryption when dropped from RigEK (application/x-msdownload).

The decode routine is affected by the version of RigEK. It corresponds only to RigEK which is used at the stage of April 20, 2017.

## Usage
```
$ php decoder.php [input] [output]
```

For example
```
$ php src/decoder.php test/input.bin test/output.bin
$ md5sum test/output.bin test/answer.bin
```

## LICENSE
```Binary_Decoder``` is open-sourced software licensed under the [MIT License](LICENSE)