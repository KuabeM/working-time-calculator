# Working Time Calculator

Small utility to store and calculate the time spent at work.

## Usage

```
    working-time-calc <SUBCOMMAND> -s <file>
```

where the available subcommands are

  - `start` writes current time to the file specified in `-s`
  - `stop` checks if a `start` entry is in `file` and calculates the working time, aborts if no `start` entry is found
  - `stats` prints current statistics 
