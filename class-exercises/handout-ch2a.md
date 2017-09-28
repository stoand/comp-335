# Handout Ch 2A

### Performance

a) Computer X
b) Performance of Computer X = 1/5, Computer Y = 1/10

### Performance Ratio

a) Computer A
b) A: 1/10 B: 1/15
c) A is 15/10 = 1.5 times faster than B

### CPU Time

B Freq: `1.2 * 100 * (10/6) = 200 Mhz`

## Clock Cycle Time

Computer A `(10 * 2) = 20 nsec` per instruction; Computer B `(20 * 1.2) = 24 nsec` per instruction

Computer A is faster as it requires 4 nsec less to complete an instruction

## Average CPI

CPI = `( 5 * 10 + 8 * 20 + 4 * 40 ) / ( 10 + 20 + 40 ) = 5.29`

## CPI for Code Sequences

a) Seq 1 Len = `2 + 1 + 2 = 5`; Seq 2 Len = `4 + 1 + 1 = 6`

b)

Seq 1 Cycles = `2 * 1 + 1 * 2 + 2 * 3 = 10` \
Seq 2 Cycles = `4 * 1 + 1 * 2 + 1 * 3 = 9` \
 __Seq 2__

c) 

Seq 1 CPI = `10 / (2 + 1 + 1) = 2`\
Seq 2 CPI = `9 / (4 + 1 + 1) = 1.5`

