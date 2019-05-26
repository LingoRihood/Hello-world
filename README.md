# Hello-world
Just another repository
print('Hello World!')
# And here is my poker code
suits = ['♠', '♦', '♥', '♣']
def want_card(card):
    if card[:2] == "黑桃":
        suit = suits[0]
        number = card[2]
    elif card[0:2] == "方片":
        suit = suits[1]
        number = card[2]
    elif card[0:2] == "红心":
        suit = suits[2]
        number = card[2]
    elif card[:2] == "梅花":
        suit = suits[3]
        number = card[2]
    print('┌────┐')
    print('│ {}      │'.format(number))
    print('│        │')
    print('│        │')
    print('│   {}    │'.format(suit))
    print('│        │')
    print('│        │')
    print('│      {} │'.format(number))
    print('└────┘')

want_card("梅花3")
want_card("红心K")
want_card("方片A")
want_card("黑桃1")
