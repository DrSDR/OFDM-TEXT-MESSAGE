ofdm text message

fs = 48khz

ofdm has a pilot block and a data block 

the ofdm symbol is 1024 samples  and 1024 fft size

the ofdm symbol freq bins are  128zeros  768samples  128zeros = 1024 samples total
there is a pilot ofdm symbol  and a data symbol
each have a cyclic prefix of 96 samples

the signal has a pulse at the start 1024 sample long

after the pulse is a 100 sample gap in time

so the whole signal is

pulse 1024 samples

gap  100 samples

pilot block cp = 96 samples

pilot block = 1024 samples

data block cp = 96 samples

data block = 1024 samples




text is 96 char or 768 bits
bits are bpsk mod
bit 0 = 180 degrees 
bit 1 = 0 degrees

the signal does have a freq offset,  use the pulse for sync and freq offset measure.

text has amazon gift card


first 8 bits are:  01110011

msb is sent first
each char is 8bits long


data block phase is related to the pilot block

good luck







