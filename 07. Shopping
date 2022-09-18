peters_budget = float(input())
video_cards_order = float(input())
cpu_order = float(input())
ram_order = float(input())

video_card_price = 250 * video_cards_order
cpu_price = (video_card_price * 0.35) * cpu_order
ram_price = (video_card_price * 0.10) * ram_order

total_price = video_card_price + cpu_price + ram_price

if video_cards_order > cpu_order:
    total_price = total_price - (total_price * 0.15)

if peters_budget > total_price:
    print(f"You have {peters_budget - total_price} leva left!")
else:
    print(f"Not enough money! You need {abs(peters_budget - total_price):.2f} leva more!")
