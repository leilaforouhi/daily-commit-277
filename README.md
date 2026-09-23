def build_histogram(numbers):
    histogram = {}

    for number in numbers:
        histogram[number] = histogram.get(number, 0) + 1

    return histogram


if __name__ == "__main__":
    values = [1, 2, 2, 3, 1, 2, 4, 3, 3]

    print("Values:", values)
    print("Histogram:", build_histogram(values))
