# Main Jet Calculator

Find it in operation at: http://mitchellwaite.ca/MainJetCalculator/

This calculator is essentially a linear interpolation of carburetor jet conversion charts found online. It will give you a good main jet to start when tuning a carburetor for a new altitude or temperature range.

The chart data was analyzed in excel to determine an approximate formula for the jet correction factor. The results are available in `JetCharts.xlsx`.  There's an R^2 value of 0.991, and the residual plots don't seem to show any bias.

The formula for the correction factor (from excel) was then written in javascript. It's not terribly complex, so the final application is a single, self-contained html file.

## Source Charts

http://www.nightrider.com/biketech/main_jet_correction.htm
http://www.ultralightnews.ca/rotax503/rotax2strokepdf/mainjetcorrectionchart.pdf
