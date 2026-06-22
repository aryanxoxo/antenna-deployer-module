# Test Notes

Clean public archive of test notes for the antenna deployer module. Values are placeholders unless explicitly marked as measured in a public artifact.

## Bench Checks

- Visual PCB inspection
- Power rail check with current limit
- Continuity check across release path
- Inhibit-state verification
- Command-state verification
- Post-test inspection

## Deployment Test Record

| Test | Setup | Expected Result | Result |
| --- | --- | --- | --- |
| Continuity check | DMM across public-safe test points | Closed path before release | placeholder |
| Safe-state check | Inhibit asserted | No release action | placeholder |
| Command check | Release command issued | Release path energizes | placeholder |
| Release timing | Controlled bench fixture | Release within target window | placeholder |
| Post-test inspection | Visual and electrical inspection | No unexpected damage | placeholder |

## What To Measure Privately

- Release current waveform
- Release time distribution over repeated tests
- PCB thermal rise around release path
- Inhibit leakage/current draw
- Harness continuity before and after vibration exposure
- Deployment success after thermal cycling
