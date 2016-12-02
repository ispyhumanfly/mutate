# Mutate
Massively parallel media transcoder for high performance computing environments.

## Synopsis

### Example: Basic Usage

Check out the available command presets before diving in...

    mpresets mreader mwriter

Search the file system for supported media files...

    mreader ~/Media1 /var/media2/

Easily convert any supported media type to another...

    mwriter -p webm480 file.mp4 output.webm

### Example: Scheduling Mutate Tasks

    mwriter -p webm1080 -t my_video.mp4 my_smaller_video.webm

## License
MIT

## Copyright
2015 - 2017 Dan Stephenson (ispyhumanfly)
