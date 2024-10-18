Q = float(input(“Enter the value of Load in kN: “)) * 1000 # converting kN to N
N = int(input(“Enter the number of data values of radial distance: “))
Z = float(input(“Enter the depth in meters: “)) # Depth is constant
R = []
# Getting radial distances
For I in range(1, N+1):
 Value_r = float(input(f”Enter radial distance {i} in meters: “))
 r.append(value_r)
# Calculate and display stress for each radial distance
For value_r in r:
 Stress = (3 * Q) / (2 * math.pi * Z**2) * ((1 / (1 + (value_r/Z)**2)) ** 2.5)
 Print(f”Radial distance: {value_r} m, Stress: {stress} N/m^2”)
