# CMDB (command data base)

This small tool helps me record and access commands I use frequently. You'd normally just use your shell history for this, but after having my shell history deleted a couple of times and for the convenience of having all my day-to-day commands in one gitable location, I decided it's worth the effort.

## Installation 
So that's it - no installation needed, just clone the repo and you're good to go. For optimal experience add the repo to your path.

## Usage

```bash
cmdb
```

<img src="https://github.com/kobibarhanin/cmdb/blob/main/examples/usage.png?raw=true"
    width="450px" border="0" alt="help">

### To view recorded commands:

```bash
cmdb show
```

<img src="https://github.com/kobibarhanin/cmdb/blob/main/examples/show.png?raw=true"
    width="450px" border="0" alt="help">

### To run a command:

```bash
cmdb run <command number> <parameters>
```

_if a command is not specified the commands db is showed_

<img src="https://github.com/kobibarhanin/cmdb/blob/main/examples/run.png?raw=true"
    width="450px" border="0" alt="help">

### To add a new command:

```bash
cmdb add '<command >'
```

### To edit commands:

```bash
cmdb edit
```

## Notes:
* In edit mode - make sure to leave a trailing blank line at the end of the file.
* Parameters are concatenated to the end of the command (may change in the future).
* Feel free to contribute.
