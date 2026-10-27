# DeepBinary

DeepBinary evaluates AI agents on open-ended vulnerability discovery in Windows kernel binaries. Each task assigns an agent one primary binary on a fixed Windows build. The agent receives no vulnerability report, designated entry point, seed proof of concept, or expected bug count; it decides where to investigate, tests hypotheses, and documents candidate findings with reproducing inputs and root-cause evidence.

The benchmark measures sustained binary analysis across models and agent setups under controlled output-token budgets. Raw discovery reports are tracked separately from later reproduction and duplicate review. The current study covers 12 primary Windows kernel targets on build 26100.7462.

## Submission rules

We are not accepting public submissions at this time. Please do not upload binaries, symbols, VM images, PoCs, or unpublished vulnerability details through issues or pull requests.

## License Issues

We are coordinating with Microsoft on licensing and redistribution terms for the benchmark materials. We will update this repository when those discussions are resolved.

## Contact

For questions about the project, please contact jk142@illinois.edu, hwiwonl2@illinois.edu, or dongjun6@illinois.edu.
