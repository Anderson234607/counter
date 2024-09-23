# Starknet Counter Contract

Simple Contract developed in Cairo Language, Starknet


# Requirements

Cairo Language

Scarb

Starkli

Starknet-devnet

# Homework 01

## Increase Counter Test

anderson@anderson-System-Product-Name:~/cairo_projects/counter$ starkli call 0x041b8cd841f681ea13a9849651728bc2dc9855ce1f238287fcc4894fb1ec9010 get_contador
[
    "0x0000000000000000000000000000000000000000000000000000000000000012"
]

anderson@anderson-System-Product-Name:~/cairo_projects/counter$ starkli invoke 0x041b8cd841f681ea13a9849651728bc2dc9855ce1f238287fcc4894fb1ec9010 increase_contador
Enter keystore password: 
Invoke transaction: 0x05df7a78917b6cc78f3e3cca7a5e1fa0629ac3ce600de5339cc038660b822d7a

anderson@anderson-System-Product-Name:~/cairo_projects/counter$ starkli call 0x041b8cd841f681ea13a9849651728bc2dc9855ce1f238287fcc4894fb1ec9010 get_contador
[
    "0x0000000000000000000000000000000000000000000000000000000000000013"
]

## Password for tests

25012501



