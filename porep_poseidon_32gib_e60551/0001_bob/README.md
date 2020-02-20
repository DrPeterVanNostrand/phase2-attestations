# Participant Attestation

Name: Bob

Organization:

Time Slot: [2020-02-26 00:00:00 UTC, 2020-02-27 12:00:00 UTC)

Attestation Signing Key: https://keybase.io/bob

Circuit ID: PoRep-Poseidon-32GiB-e6055a1

Participant Number: 1

Contribution Hash: 47cd37f99d02dbf65240122463792b4b0ed65a99c18474d2d5463c616ed865e114569c20a19bae0fd770f14a536593046cb7d2f1f1df2522ac24c0e8e524d3e2

### Hardware

Instance Type:

Processor: Intel(R) Xeon(R) Gold 5218 CPU @ 2.30GHz

Available RAM:

Number of Processors:

### Files

#### Previous Participant's Phase2 File

- Download URL: https://trusted-setup.s3.eu-central-1.amazonaws.com/porep_poseidon_32gib_e6055a1_0

- BLAKE2 Digest: ae2b5dd4dfafeb8f90491fa5567c4177f4e60f15bed429c6fbe892dacb128eedb9b8978706b906ff633193fe3f0ea9d3856982c047a24af82bd6feda522afd2b

#### Phase2 File Containing Your Contribution

- Upload URL: https://trusted-setup.s3.eu-central-1.amazonaws.com/porep_poseidon_32gib_e6055a1_1

- BLAKE2 Digest: ffffffffdfafeb8f90491fa5567c4177f4e60f15bed429c6fbe892dacb128eedb9b8978706b906ff633193fe3f0ea9d3856982c047a24af82bd6feda12345678

### Log

```
$ RUST_BACKTRACE=1 RUST_LOG=info ./target/release/phase2 contribute porep_poseidon_32gib_e6055a1_0
22:33:19 [ INFO] contributing randomness to params for circuit: PoRep Poseidon 32GiB e6055a1
22:33:19 [ INFO] reading params from disk: porep_poseidon_32gib_e6055a1_0
00:09:06 [ INFO] successfully read params from disk, dt=5746s
00:09:06 [ INFO] making contribution
00:10:02 [ INFO] successfully made contribution, contribution hash: 47cd37f99d02dbf65240122463792b4b0ed65a99c18474d2d5463c616ed865e114569c20a19bae0fd770f14a536593046cb7d2f1f1df2522ac24c0e8e524d3e2, dt=55s
00:10:02 [ INFO] verifying new params match circuit
00:17:46 [ INFO] successfully verified new params match circuit, all_contributions.len()=1, dt=462s
00:17:46 [ INFO] successfully verified new params contain new contribution
00:17:46 [ INFO] writing new params to disk: porep_poseidon_32gib_e6055a1_1
00:17:51 [ INFO] finished writing new params to disk, dt=4s
00:17:51 [ INFO] successfully made contribution, dt_total=6271s
```
