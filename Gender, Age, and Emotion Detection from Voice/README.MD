## About Dataset

<b>Context:</b>

Our target was to predict gender, age, and emotion from audio. We found audio labeled datasets on Mozilla and RAVDESS. So by using R programming language, 20 statistical features were extracted and then after adding the labels, these datasets were formed. Audio files were collected from "Mozilla Common Voice" and “Ryerson AudioVisual Database of Emotional Speech and Song (RAVDESS)”.

<b>Content:</b>

Datasets contain 20 feature columns and 1 column for denoting the label. The 20 statistical features were extracted through the Frequency Spectrum Analysis using R programming Language. They are:

<pre>
1) <b>meanfreq</b>   - The mean frequency (kHz) is a pitch measure that assesses the center of the distribution of power across frequencies.
2) <b>sd</b>         - The standard deviation of frequency is a statistical measure that describes a dataset’s dispersion relative to its mean and is calculated as the variance’s square root.
3) <b>median</b>     - The median frequency (kHz) is the middle number in the sorted, ascending, or descending list of numbers.
4) <b>Q25</b>        - The first quartile (in kHz), referred to as Q1, is the median of the lower half of the data set. This means that about 25 percent of the data set numbers are below Q1, and about 75 percent are above Q1.
5) <b>Q75</b>        - The third quartile (in kHz), referred to as Q3, is the central point between the median and the highest distributions.
6) <b>IQR</b>        - The interquartile range (in kHz) is a measure of statistical dispersion, equal to the difference between the 75th and 25th percentiles or between upper and lower quartiles.
7) <b>skew</b>       - The skewness is the degree of distortion from the normal distribution. It measures the lack of symmetry in the data distribution.
8) <b>kurt</b>       - The kurtosis is a statistical measure that determines how much the tails of the distribution vary from the tails of a normal distribution. It is actually the measure of outliers present in the data distribution.
9) <b>sp.ent</b>     - The spectral entropy is a measure of signal irregularity that sums up the normalized signal’s spectral power.
10) <b>sfm</b>       - The spectral flatness or tonality coefficient, also known as Wiener entropy, is a measure used for digital signal processing to characterize an audio spectrum. Spectral flatness is usually measured in decibels, which, instead of being noise-like, offers a way to calculate how tone-like a sound is.
11) <b>mode</b>      - The mode frequency is the most frequently observed value in a data set.
12) <b>centroid</b>  - The spectral centroid is a metric used to describe a spectrum in digital signal processing. It means where the spectrum’s center of mass is centered.
13) <b>meanfun</b>   - The meanfun is the average of the fundamental frequency measured across the acoustic signal.
14) <b>minfun</b>    - The minfun is the minimum fundamental frequency measured across the acoustic signal.
15) <b>maxfun</b>    - The maxfun is the maximum fundamental frequency measured across the acoustic signal.
16) <b>meandom</b>   - The meandom is the average of the dominant frequency measured across the acoustic signal.
17) <b>mindom</b>    - The mindom is the minimum of the dominant frequency measured across the acoustic signal.
18) <b>maxdom</b>    - The maxdom is the maximum of the dominant frequency measured across the acoustic signal.
19) <b>dfrange</b>   - The dfrange is the range of the dominant frequency measured across the acoustic signal.
20) <b>modindx</b>   - the modindx is the modulation index, which calculates the degree of frequency modulation expressed numerically as the ratio of the frequency deviation to the frequency of the modulating signal for a pure tone modulation.
</pre>
