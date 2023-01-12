import qrcode
import os

#website link
url = input("Please enter a website link: ")
#generate image
img = qrcode.make(url)

#location to save image
print("Please select a location to save the qr code image:")
print("1. Formerly used location")
print("2. Default/dedicated folder")
print("3. Add a new location")
choice = int(input())

if choice == 1:
    save_location = input("Please enter the formerly used location: ")
elif choice == 2:
    save_location = input("Please enter the default/dedicated folder: ")
elif choice == 3:
    save_location = input("Please enter the new location: ")

img.save(save_location)
print("QR code image saved successfully!")
