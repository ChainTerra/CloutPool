# CloutPool

Hard Fork of [Not-Only-Mining-Pool](https://github.com/mining-pool/not-only-mining-pool) to run the Keccak mining implementation for BitClout.

## Running
Make sure to run the bitclout/core daemon (Dockerfile and node) first locally. \
Run `go build .` \
Copy `go-stratum-pool` and rename `config.btclt.json` to `config.json` \
Change the `rewardRecipients` address in line 18 of the config, to your address. \
Run `./go-stratup-pool` and it should detect the `config.json` file and node automatically.

**Special thanks to:** \
[@C0MM4ND](https://github.com/C0MM4ND) for creating the [not-only-mining-pool](https://github.com/mining-pool/not-only-mining-pool) in go. \
[@maebeam](https://github.com/maebeam) for helping w/ lots of my GitHub issues.


[![Bitclout](https://img.shields.io/badge/-Follow%20me%20on%20BitClout-red)](https://bitclout.com/u/AMKN) | [![Bitclout](https://img.shields.io/badge/-Follow%20CloutPool%20on%20BitClout-Yellow)](https://bitclout.com/u/CloutPool)

#### PLEASE KEEP IN MIND THIS IS EXPERIMENTAL, AND DEVELOPMENT MAY NOT YET BE CONSIDERED STABLE.
