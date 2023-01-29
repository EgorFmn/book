$ forge init hello_foundry
$ cd hello_foundry
$ tree . -d -L 1
.
├── lib
├── script
├── src
└── test

4 directories
$ forge build
Compiling 10 files with 0.8.16
Solc 0.8.16 finished in 3.97s
Compiler run successful
$ forge test
No files changed, compilation skipped

Running 2 tests for test/Counter.t.sol:CounterTest
[PASS] testIncrement() (gas: 28312)
[PASS] testSetNumber(uint256) (runs: 256, μ: 27376, ~: 28387)
Test result: ok. 2 passed; 0 failed; finished in 24.43ms
