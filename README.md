# e1039-online-reco

A set of scripts to control the online reconstruction at E1039.

The e1039-core library (`e1039-core/packages/kTThreads`) does not work as is.
A modified version is being used for now, as seen in `setup.sh`.


## Usage

```
source setup.sh
./watch_sraw_data.sh
```


## Notes

The ROOT macro is based on `/data2/e1039/core/default/macros/packages/kTThreads/RunScheduler.C`.
