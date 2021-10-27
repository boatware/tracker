# Tracker

A simple time tracker for bash that allows you to track time in a versionable file.

## Prerequisities

- bash

## Installation

- Clone this repository to a destination of your choice: `git clone REPO DIR`
- To install it systemwide copy the file `tracker` to `/usr/local/bin`: `sudo cp DIR/tracker /usr/local/bin/.`

## Usage

After installation you can open a terminal at every place and run the tracker:

```bash
$ tracker
```

It will then start tracking the time.

To stop it, just press Ctrl+C. You will then be asked for a comment to the tracked time. For example "Added README" - kinda like a git commit.

The tracked time will be saved as CSV file like the following:

```bash
2021-10-27 15:13:53,2021-10-27 15:14:01,00:00:10,comment
2021-10-27 15:14:23,2021-10-27 15:14:25,00:00:03,comment
```

The first column is always the start time, the second is the end time. The third column holds the elapsed time and the last column the comment.
