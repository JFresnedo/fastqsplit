# fastqsplit

Splits fastq files by lane.

Takes gzipped fastq files of the form "prefix_suffix" and writes gzipped files of the form "prefix_lane_suffix".

## Usage

fastqsplit fastq_file(s)

## Notes

* fastq files must be gzipped
* Does approximately 10M lines every 13s (depending on CPU speed)

## Building
```
go get github.com/klauspost/pgzip/
go build fastqsplit.go
```

## Binaries
Download binaries for Linux or OSX from the releases page.
