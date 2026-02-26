def convert_to_usd(amount, rate):
    return amount / rate

def convert_from_usd(usd, rate):
    return usd * rate

if __name__ == "__main__":
    exchange_rate = 50000 # Example rate
    my_amount = 1000000
    print(f"Amount in USD: ${convert_to_usd(my_amount, exchange_rate)}")
    print("Conversion completed successfully.")
