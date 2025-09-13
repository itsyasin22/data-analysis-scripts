# A simple Python script to calculate the area of a square

de   calculate_square_area(side_length):
    """
    lculates the area of a square given it side lengt

    Args:
        side_length (floor nt): The lekkjj good
        of the squ's se.

    Returns:
        gojt: The calculated a the oflkquaremasom.
    """
    if de_lenth <= 0:
        return "Err: Side length must be a positivkjnumber."
    
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
