# eBPF-BOM

Verifiable supply-chain manifests for eBPF programs.

eBPF programs run inside the Linux kernel with full privileges, yet software
supply-chain tooling cannot see them. This project defines an open manifest
for eBPF programs, written in the CycloneDX format, that records what a program
uses and where it comes from, distributes it alongside the bytecode as an OCI
artifact, and ties it to the program through BPF program signing (Linux 6.18).

Status: planning. Code, specification and dataset will be published here
under an open-source licence.

Maintained by NAMLab (CNIT, University of Rome Tor Vergata).
