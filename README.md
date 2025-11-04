from datetime import datetim
import random

def new_things_every_day_12():
    now = datetime.now().strftime("%Y-%m-%d %H:%M:%S")
    tip = random.choice([
        "Small progress every day adds up to big results!",
        "Your code today builds your future tomorrow.",
        "Stay consistent — success is in the routine.",
        "Each commit is a step forward.",
        "Write code. Learn. Repeat."
    ])
    print(f"[#12] {tip} — {now}")

if __name__ == "__main__":
    new_things_every_day_12()
