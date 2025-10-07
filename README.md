from datetime import datetime

def current_time():
    return datetime.now().strftime("%H:%M:%S")

if __name__ == "__main__":
    print(f"Current time is: {current_time()}")
