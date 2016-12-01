# Mutate
A massively parallel audio and video transcoding solver.

## Synopsis

### Basic Usage

Check out the available command presets before diving in...

    mpresets mreader mwriter

Search the file system for media files...

    mreader ~/Media1 /var/media2/

Easily convert any supported media type to another...

    mwriter -p webm480 file.mp4 output.webm

### Batch Usage

    mwriter -p webm1080 -t my_video.mp4 my_smaller_video.webm

## License
MIT

## Copyright
2015 - 2017 Dan Stephenson (ispyhumanfly)
