import  unicodedata
def  emoji_to_text(emoji):
    try:        
        return unicodedata.name(emoji)
    except ValueError:
        return None
emoji=input("Enter an emoji:")
text=emoji_to_text(emoji)
if text:
    print(f"The text representation of {emoji} is : {text}")
else: 
   print("Invalid emoji.")
