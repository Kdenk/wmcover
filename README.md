# wmcover
webMAN MOD cover creator &amp; FTP uploader

wmcover creates a cover to be used in webMAN Games for PS1, PS2, PS3, PSP or of custom size.
A transparent border is applied to display a gap between covers when out of focus.

## Usage

    ./wmCover [option]... [preset] [input] [output]
  
### Options
    -noftp                      dont't upload cover via FTP
    -ip [ip]                    FTP host IP address (default value: 192.168.1.103)
    -path [path]                FTP host upload directory
    -size [<width>x<height>]    cover size in pixels
There's no defalut value for path and size, they need to be set via options or presets.

### Presets
    -ps1    PS1 preset (default values: path=/dev_hdd0/PSXISO and size=180x180)
    -ps2    PS2 preset (default values: path=/dev_hdd0/PS2ISO and size=130x180)
    -ps3    PS3 preset (default values: path=/dev_hdd0/PS3ISO and size=156x180)
    -psp    PSP preset (default values: path=/dev_hdd0/PSPISO and size=106x180)

### Input
Input image file to convert (use quotes if there are spaces in filename).

### Output
Output cover filename without extension (defaults to .png, ok spaces without quotes).
