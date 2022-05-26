a.	Background: we should find the sat with our antenna(northish) we should keep track of it while it moves, we should get the signal demodulate and get the flag.

b.	There is the status server, there is a server for az/el commands, and a server for receiving samples from.

c.	We connected all 3 servers, found an initial point that we get the signal from followed the signal using it’s power and a simple tracking algorithm, and saved the whole signal.

d.	Demodulation: down sample by 10, combining I/Q bit by bit, the sign of the symbol is a good enough decision rule as a modem, we built bytes out of every 8 bits with right msb, and converted it to ascii chars.
