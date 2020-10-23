# DSC MOI Python task one
This example project is written in Python, and tested with pytest.



### Setup command
`sudo -H pip3 install pytest`

### Run command
`pytest`

### The assignment
>In the United Kingdom the currency is made up of pound (£) and pence (p). There are eight coins in general circulation:
1p, 2p, 5p, 10p, 20p, 50p, £1 (100p), and £2 (200p).
It is possible to make £2 in the following way:
1×£1 + 1×50p + 2×20p + 1×5p + 1×2p + 3×1p
Write a Python program to find different ways where £2 be made using any number of coins.

### Notes
- pip's install path is not included in the PATH var by default, so without installing via `sudo -H`, pytest would be unaccessible.
- The tests are failing right now because the method isn't outputting the correct string. Fixing this up will make the tests green.