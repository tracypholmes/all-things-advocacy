# Detecting Cryptocurrency Mining With eBPF

## Abstract

eBPF allows for introspection of events across entire nodes and is a powerful foundation for collecting data from different workloads on a Kubernetes cluster. This talk will explore step-by-step a cryptocurrency mining attack, showing how it behaves, evolves, and how different stages of the attack can be detected using open source eBPF-based tools.

As a demonstration, a live miner barely detectable using traditional userspace tools will be shown on a pod. Using tools like Cilium’s project Tetragon and leveraging eBPF’s kernel-based network and process-level visibility, malicious behaviors such as suspicious processes and unexpected outbound connections are easily identified. As a result, the detected miner will be blocked, and the cluster defended.

Attendees will leave with ideas for protecting Kubernetes clusters, as well as an understanding of how eBPF-based tools can operate across an entire Kubernetes cluster without any modification to applications or their configuration.

## Relevant Links

- [eCHO episode #54 - Tetragon w/ Natália Ivánkó (with demo!)](https://youtu.be/vVFg8WkaeeM)
- [eCHO (eBPF & Cilium Office Hours)](https://www.youtube.com/@eBPFCilium)
- [Tetragon Setup](https://github.com/cilium/tetragon)
- [ARM support for Tetragon - GH issue #487](https://github.com/cilium/tetragon/issues/487)
- [Pixie blog post - Detecting Monero miners with bpftrace](https://blog.px.dev/detect-monero-miners/)


