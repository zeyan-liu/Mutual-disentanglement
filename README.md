
# Mutual Disentanglement Strategy for Voice Anonymization

*Anonymous submission*

## Abstract

Voice anonymization seeks to eliminate speaker information from speech signals while maintaining linguistic content and prosody. In state-of-the-art disentanglement-based voice anonymization frameworks, achieving a balance between de-identification and the preservation of original speech prosody poses a significant challenge. Current methods disentangle prosody and speaker attributes independently, neglecting their interdependent effects. This leads to the leakage of both prosody and speaker attributes within the other representations. To this end, this paper proposes a mutual disentanglement strategy that simultaneously mitigates speaker information during prosody disentanglement and reduces prosody information during speaker disentanglement. Experiments conducted on the VoicePrivacy 2024 benchmark show that the strategy improves privacy protection with better prosody preservation. Audio samples are available at https://anonymous.4open.science/r/Mutual-disentanglement-D5E0.

---

## Audio Samples

The audio samples are organized by framework and method.

- `IDMap-Diff w/o MD` denotes the IDMap-Diff baseline without mutual disentanglement.
- `IDMap-Diff w/ MD` denotes IDMap-Diff with the proposed mutual disentanglement strategy.
- Only IDMap-Diff samples are shown in this demo page.

---

## x-vector based

| File name | IDMap-Diff w/o MD | IDMap-Diff w/ MD |
|---|---|---|
| `1462-170142-0000.wav` | [audio](x-vector%20based/idmap-diff/1462-170142-0000.wav) | [audio](x-vector%20based/idmap-diff-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](x-vector%20based/idmap-diff/1462-170142-0001.wav) | [audio](x-vector%20based/idmap-diff-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](x-vector%20based/idmap-diff/84-121550-0000.wav) | [audio](x-vector%20based/idmap-diff-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](x-vector%20based/idmap-diff/84-121550-0001.wav) | [audio](x-vector%20based/idmap-diff-w/84-121550-0001.wav) |

---

## STTTS

| File name | IDMap-Diff w/o MD | IDMap-Diff w/ MD |
|---|---|---|
| `1462-170142-0000.wav` | [audio](STTTS/idmap-diff/1462-170142-0000.wav) | [audio](STTTS/idmap-diff-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](STTTS/idmap-diff/1462-170142-0001.wav) | [audio](STTTS/idmap-diff-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](STTTS/idmap-diff/84-121550-0000.wav) | [audio](STTTS/idmap-diff-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](STTTS/idmap-diff/84-121550-0001.wav) | [audio](STTTS/idmap-diff-w/84-121550-0001.wav) |

---

## Asrbn

| File name | IDMap-Diff w/o MD | IDMap-Diff w/ MD |
|---|---|---|
| `1462-170142-0000.wav` | [audio](asrbn/idmap-diff/1462-170142-0000.wav) | [audio](asrbn/idmap-diff-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](asrbn/idmap-diff/1462-170142-0001.wav) | [audio](asrbn/idmap-diff-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](asrbn/idmap-diff/84-121550-0000.wav) | [audio](asrbn/idmap-diff-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](asrbn/idmap-diff/84-121550-0001.wav) | [audio](asrbn/idmap-diff-w/84-121550-0001.wav) |

---

## Asrbn-F0

| File name | IDMap-Diff w/o MD | IDMap-Diff w/ MD |
|---|---|---|
| `1462-170142-0000.wav` | [audio](asrbn-f0/idmap-diff/1462-170142-0000.wav) | [audio](asrbn-f0/idmap-diff-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](asrbn-f0/idmap-diff/1462-170142-0001.wav) | [audio](asrbn-f0/idmap-diff-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](asrbn-f0/idmap-diff/84-121550-0000.wav) | [audio](asrbn-f0/idmap-diff-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](asrbn-f0/idmap-diff/84-121550-0001.wav) | [audio](asrbn-f0/idmap-diff-w/84-121550-0001.wav) |

---

## Proposed

| File name | IDMap-Diff w/o MD | IDMap-Diff w/ MD |
|---|---|---|
| `1462-170142-0000.wav` | [audio](Proposed/idmap-diff/1462-170142-0000.wav) | [audio](Proposed/idmap-diff-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](Proposed/idmap-diff/1462-170142-0001.wav) | [audio](Proposed/idmap-diff-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](Proposed/idmap-diff/84-121550-0000.wav) | [audio](Proposed/idmap-diff-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](Proposed/idmap-diff/84-121550-0001.wav) | [audio](Proposed/idmap-diff-w/84-121550-0001.wav) |

---

## Proposed w/o MD

| File name | IDMap-Diff w/o MD | IDMap-Diff w/ MD |
|---|---|---|
| `1462-170142-0000.wav` | [audio](Proposed%20wo%20MD/idmap-diff/1462-170142-0000.wav) | [audio](Proposed%20wo%20MD/idmap-diff-w/1462-170142-0000.wav) |
| `1462-170142-0001.wav` | [audio](Proposed%20wo%20MD/idmap-diff/1462-170142-0001.wav) | [audio](Proposed%20wo%20MD/idmap-diff-w/1462-170142-0001.wav) |
| `84-121550-0000.wav` | [audio](Proposed%20wo%20MD/idmap-diff/84-121550-0000.wav) | [audio](Proposed%20wo%20MD/idmap-diff-w/84-121550-0000.wav) |
| `84-121550-0001.wav` | [audio](Proposed%20wo%20MD/idmap-diff/84-121550-0001.wav) | [audio](Proposed%20wo%20MD/idmap-diff-w/84-121550-0001.wav) |
