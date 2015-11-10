# Moisture
Towel's development interpreter. This Python interpreter is not meant for production use, but rather to test new features fast. 

## Some notes on structure
The `help` function is exclusive to the REPL. Loops are searched for when opening a file, and therefore aren't available in the REPL (this should be fixed sometime, though).

