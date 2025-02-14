cube.py
edge_length = int(input("Enter the length of the cube's edge: "))
surface_area = 6 * (edge_length ** 2)
print("The surface area of the cube is:", surface_area)

momentum.py
mass = float(input("Enter the object's mass in kilograms: "))
velocity = float(input("Enter the object's velocity in meters per secod: "))
momentum = mass * velocity
print(f"The object's momentum is {momentum:.2f} kg.m/s")

sphere.py
import math
radius = float(input("Enter the radius of the sphere: "))
diameter = 2 * radius
circumference = 2 * math.pi * radius
surface_area = 4 * math.pi * (radius ** 2)
volume = (4/3) * math.pi * (radius ** 3)
print("Sphere Calculations:")
print(f"Diameter: {diameter:.2f}")
print(f"Circumference: {circumference:.2f}")
print(f"Surface_area: {surface_area:.2f}")
print(f"Volume: {volume:.2f}")
