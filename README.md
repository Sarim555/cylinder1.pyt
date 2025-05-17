import math

def calculate_cylinder(radius, height):
    # Volume of cylinder
    volume = math.pi * radius ** 2 * height
    
    # Total surface area of cylinder
    surface_area = 2 * math.pi * radius * (radius + height)
    
    return volume, surface_area

# User input
r = float(input("Enter the radius of the cylinder: "))
h = float(input("Enter the height of the cylinder: "))

# Calculations
volume, surface_area = calculate_cylinder(r, h)

# Results
print(f"Volume of the cylinder: {volume:.2f} cubic units")
print(f"Total Surface Area of the cylinder: {surface_area:.2f} square units")
