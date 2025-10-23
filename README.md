# zk-game

```
nargo new <NAME>
cd <NAME>
nargo compile

# Create Prover.toml
nargo check

# Create witness
nargo execute

# Create verification key
bb write_vk --oracle_hash keccak -b ./target/<NAME>.json -o ./target

# Create verifier contract
bb write_solidity_verifier -k ./target/vk -o ./target/Verifier.sol
```
