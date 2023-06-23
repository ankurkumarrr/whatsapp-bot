# Whatsapp-Bulk-Messenger

This bot allows for the user to send messages (text + images) to multiple users fully automated.

Note: The `error.txt` file contains all the numbers that failed to receive the messages. 

# Requirements

*  Python >= 3.6

# Setup

1. Install latest python version 
2. Run `pip install -r requirements.txt`

# Steps

1. Enter the message you want to send inside `message.txt` file.
2. Enter the list of numbers line-separated in `numbers.txt` file.
3. Keep the image file that needs to be sent in the same directory as the `automator.py` 
4. Tweak the `automator.py` with the image file location (read how the already existing image file `barberaa.jpeg` location is written). 
5. Run `python automator.py`.
6. Once the program starts, you'll see the message in message.txt and count of numbers in the numbers.txt file.
7. After a while, Chrome should pop-up and open web.whatsapp.com.
8. Scan the QR code to login into whatsapp.
9. Press `Enter` to start sending out messages.
10. Sit back and relax!
