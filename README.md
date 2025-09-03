# A simple Python script to calculate the area of a square

def calculate_square_area(side_length):
    """
    Calculates the area of a square given its side length.

    Args:
        side_length (float or int): The length of the square's side.

    Returns:
        float: The calculated area of the square.
    """
    if side_lenth <= 0:
        return "Error: Side length must be a positive number."
    
    area = side_length ** 2
    return area

# Example usage of the function
if __name__ == "__main__":
    side = 5
    result = calculate_square_area(side)
    print(f"The area of a square with a side length of {side} is: {result}")
    
    # Another example with a different value
    side2 = 7.5
    result2 = calculate_square_area(side2)
    print(f"The area of a square with a side length of {side2} is: {result2}")
