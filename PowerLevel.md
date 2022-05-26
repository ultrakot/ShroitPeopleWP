a.	We connected to the server
b.	Downloaded the signal using the get_sample.py script
c.	Calculated an accurate SNR by finding the carrier freq, down convert to baseband and than we got a dc with noise so it was easy to calculate mean and variance to get the SNR (10*log10(abs(m)^2/s)
