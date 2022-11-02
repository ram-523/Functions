 ``` python

input_discharges = [1000, 1500, 1900, 2000, 2500]
set_limit = 1900


def check(list):
    for var in list:
        if var <= set_limit:
            print("Reservoir is in stable condition")
        elif var > set_limit:
            print("Reservoir failed")


print(check(input_discharges))

```
