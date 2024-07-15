# Desert# Function to calculate the area of a rectangle
def calculate_area(length, width):
    area = length * width
    return area

# Main program
if __name__ == "__main__":
    # Taking input from user for length and width
    length = float(input("Enter the length of the rectangle: "))
    width = float(input("Enter the width of the rectangle: "))

    # Calculating the area using the function
    area = calculate_area(length, width)

    # Displaying the result
    print(f"The area of the rectangle with length {length} and width {width} is {area}.")
