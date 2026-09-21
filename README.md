# Neural Signal Processing: From Raw Traces to Spike Train Statistics

Two linked signal-processing explorations in Python: a continuous
calcium-imaging-style recording, and a multi-neuron spike train
dataset.

## Part 1 - Signal fundamentals
Segmenting a recording into baseline/stimulus, manual resampling,
aliasing and the Nyquist limit, and the minimum bit depth needed to
resolve a given amplitude resolution.

## Part 2 - Noise reduction
SNR estimation via two methods (power-subtraction vs. amplitude
ratio), block averaging, and comparing rectangular vs. triangular
smoothing kernels.

## Part 3 - Spike train analysis
Firing rate, Fano Factor, inter-spike intervals, raster plots, PSTHs,
and auto-/cross-correlation, used to characterize and compare the
firing style of five simulated neurons (Poisson-like, regular, and
bursting).

See the notebook's "Key Findings" section at the end for the full
results table and interpretation.

## Tools

`numpy`, `pandas`, `matplotlib`, `scipy.signal`

## Running it

`Neural_data.csv` and `spike_trains.csv` are included in this repo, so
the notebook runs as-is.

## Note

This was originally submitted as a written report (PDF, included here
as `NSP_Project_1_Report.pdf`) alongside the notebook; the notebook
has also been expanded with the same explanations and conclusions as
inline markdown, so it stands on its own. The report's cover page has
been redacted (student ID and personal Colab link removed - flattened
to an image so the text isn't recoverable, not just visually hidden).
