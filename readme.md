# Go Slugify

A small command line tool that treats each input argument as a file system path and then attempts to rename it to a "slugified" version. The slugified version refers here to a string that should still represent the original meaning, but remove most special characters. No consideration was given to performance, this is mostly to convert files names to ones more easily parseable/pipeable.
