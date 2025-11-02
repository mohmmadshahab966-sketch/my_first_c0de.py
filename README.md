from datetime import datetime

name = input("👋 مرحباً! شنو اسمك؟ ")

hour = datetime.now().hour

if 5 <= hour < 12:
    greet = "صباح الخير 🌞"
elif 12 <= hour < 17:
    greet = "مساء الخير ☀️"
else:
    greet = "مساء النور 🌙"

print(f"{greet} {name}! نتمنى لك يوماً موفقاً 💪")
