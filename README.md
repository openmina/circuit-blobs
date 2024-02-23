
Use `git clone --depth 1 https://github.com/openmina/circuit-blobs.git` to avoid pulling the whole history

Various binaries used during witness generation, and testings

- All `*_gates.json` are the list of gates, for each circuit
- `*_internal_vars.bin` and `*_rows_rev.bin` are other data we need for witness generation: [link](https://github.com/MinaProtocol/mina/blob/28ad2335c3970b856849137196c7693c18edee78/src/lib/crypto/kimchi_backend/common/plonk_constraint_system.ml#L707-L710)
- All others `*.bin` are snark works (`ExternalSnarkWorkerRequest`) used for testings
- `*.txt` files are witnesses vectors generated from OCaml, they are used for testings too
