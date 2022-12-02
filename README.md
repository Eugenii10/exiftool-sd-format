# exiftool-sd-format

It is file that describes a text format in which **exiftool** should write its output.
To use this or other format file with **exiftool** you should save it somewhere on your disk (prefer pathes without spaces), and then add `-p "X:\Path\To\Your\Format\File\exif.fmt"` to the arguments when launch **exiftool** application. In Windows that could be done via a **.bat** file or a shortcut **.lnk** or directly in the command prompt.
You can read more about `-p` key here: https://exiftool.org/exiftool_pod.html#p-FMTFILE-or-STR--printFormat

My orignal purpose is to use it with **ImageGlass** image viewer while working in Stable Diffusion UI.
https://github.com/AUTOMATIC1111/stable-diffusion-webui/discussions/1569#discussioncomment-4175458
