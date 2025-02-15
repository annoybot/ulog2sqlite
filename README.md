# ulog2sqlite

Example program which uses the [yule_log](https://crates.io/crates/yule_log) parser to convert a [PX4 ULOG](https://docs.px4.io/main/en/dev_log/ulog_file_format.html) file to a SQLIte database.  

Follows [PlotJuggler](https://plotjuggler.io/) conventions for column naming.

## Usage

```shell
ulog2sqlite data/sample_log_small.ulg
```