# research-auto
# easy code for the research some key news
import random

def generate_even_number():
    return random.randrange(100, 1001, 2)

if __name__ == "__main__":
    even_number = generate_even_number()
    print("Random even number between 100 and 1000:", even_number)
