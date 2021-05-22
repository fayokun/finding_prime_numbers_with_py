def is_prime(number):
    if number <= 1:
        return False
    
    for factor in range(2, number):
        if number % factor == 0:
            return False

    return True
    
print(is_prime(9))
