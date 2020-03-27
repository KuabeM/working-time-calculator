# Stempel

Small utility to store and calculate the time spent at work.

## Usage

```bash
  stempel <SUBCOMMAND> -s <file>
```

where the available subcommands are

  - `start` writes current time to the file specified in `-s`
  - `stop` checks if a `start` entry is in `file` and calculates the working time, aborts if no `start` entry is found
  - `stats` prints current statistics 

## Planned Features

  - [ ] Statistics: pretty printinng, provide weekly, monthly,... statistics
  - [ ] Tracking: allow to specify start and stop time as cli arg
  - [ ] Tracking: cancle started work
  - [ ] Storage: don't store as seconds and nanoseconds, use something more verbose

## License

MIT
