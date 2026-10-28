<div align="center">
  <h1>DeepBinary</h1>
  <p>Can AI agents uncover deep vulnerabilities in production binaries?</p>
  <p>
    <a href="https://jongseong.kim/">Jongseong Kim</a><sup>*</sup>,
    <a href="https://hwiwonl.ee/">Hwiwon Lee</a><sup>*</sup>,
    <a href="https://smlijun.github.io/">Dongjun Kim</a>,
    <a href="https://lingming.cs.illinois.edu/index.html">Lingming Zhang</a>
  </p>
  <p><sup>*</sup> Equal contribution</p>
  <p align="center">
    <a href="https://deepbinary.so/"><img src="https://img.shields.io/badge/Leaderboard-Live-f97316?style=for-the-badge" alt="Leaderboard"></a>
  </p>
</div>
<br>

DeepBinary benchmarks AI agents on open-ended vulnerability discovery in real Windows system binaries. It evaluates sustained binary analysis through executable evidence, security impact, and estimated bounty.

## Benchmark overview

The current study covers 12 primary Windows kernel targets. Each campaign assigns an agent one primary binary on a specified Windows version under a controlled output-token budget. Agents receive no vulnerability report, designated entry point, seed proof of concept, or expected bug count. They choose where to investigate, test hypotheses, and document candidate findings with reproducing inputs and root-cause evidence.

## Evaluation

Raw discovery reports are tracked separately from subsequent reproduction and duplicate review. The leaderboard presents two result metrics:

- **Unique bugs:** Findings accepted by the benchmark’s final Judge and deduplicated within each model–target campaign. Totals are not globally deduplicated across campaigns.
- **Est. Bounty:** The sum of benchmark valuations for accepted findings, based on published MSRC award rates. These are benchmark estimates, not MSRC-confirmed awards, payouts, or eligibility determinations.

The leaderboard also shows cumulative results across output-token budgets and estimated discovery costs.

## Benchmark access

This repository provides the public project overview. The evaluation framework and benchmark materials are not publicly distributed due to security, ethical, and licensing considerations. If you would like to access the benchmark and run experiments, please contact the project team using the contact information below.

## Submission policy

Public benchmark submissions are not currently accepted. Please do not upload binaries, symbols, VM images, proofs of concept, or unpublished vulnerability details through issues or pull requests.

## Ethical considerations

Experiments with DeepBinary are intended for security research and should be conducted only in authorized environments. Potentially sensitive findings should be handled through coordinated disclosure with the affected vendor.

## Contact

For research, access, or project inquiries, please contact [jk142@illinois.edu](mailto:jk142@illinois.edu), [hwiwonl2@illinois.edu](mailto:hwiwonl2@illinois.edu), or [dongjun6@illinois.edu](mailto:dongjun6@illinois.edu).
