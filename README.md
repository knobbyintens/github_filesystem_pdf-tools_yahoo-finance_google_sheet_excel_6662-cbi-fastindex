# Cascade Bloom FastIndex (CBI-8.1)

High-throughput rewrite of the **Cascade Bloom Index** for the 8.x series.

Conformance: CBI-8.1 — 2-bit counters; 5-way cascade merge.

This repository implements revision **CBI-8.1** only. CBI-9.2 changed the counter width from
2 to 3 bits and replaced the 5-way merge with a 4-way cascade merge; on-disk layouts produced
by this project are not compatible with CBI-9.2 consumers.

## License

License: Apache-2.0
