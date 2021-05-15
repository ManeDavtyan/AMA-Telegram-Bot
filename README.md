# AMA-Telegram-Bot
Abstract:
   AMA Telegram Bot provided sends messages to the users based on an information, if they have their numbers showing in Telegram.  The warning message with the instructions      is sent in 3 languages, to make sure the user got the point of the message.

Telegram is a freeware, cross-platform, cloud-based instant messaging software and application service.
Telegram is said to be more secure than mass market messengers like WhatsApp and Line. It is based on the
MTProto protocol, built upon time-tested algorithms to make security compatible with high-speed delivery
and reliability on weak connections.
Nevertheless, the basis of security in Telegram is the responsibility of users, as it preserves user-dependant
settings of data security.
Purpose of the Project:
Unfortunately, there is a solid number of people who neglect their Telegram security mainly because of
ignorance. Considering such circumstances, our team came up with a project idea to create a Telegram Bot
to send descriptive messages with instructions on how to hide their numbers if they have not done that
already for the sake of security.
Methodology:
Our journey started with a thorough examination and discussion of the Telethon library, which would allow
us to interact with Telegram via Python and make them work for our humanitarian purpose.
Later research focused on the library’s Synchronous and Asynchronous functionalities, correlated issues
with the versions of Tornado, scalable, non-blocking web server, and application framework written in
Python.
After establishing the cooperation algorithm within the libraries and versions of required packages, we
proceeded with the most intricate part of our project, scraping code and its implementation. The first code of 
scraping worked on groups, yet it required asynchronous functionalities incompatible with tornado
versions. Later developments of the scraping code made it possible to have stable and practical cooperation
within tornado and telethon packages due to the synchronization and version control.
Final Result:
Our team successfully overcame the obstacles on our way to finishing the project, and we can proudly
claim that our efforts were not in vain.
The final code, which consists of three main chunks, meets the requirements and goals of our project.
The first chunk processes the code consisting of five steps:
1. Signing-in
2. Providing public group’s or channel’s username
3. Going through the whole group/channel and scraping the data of all users
4. Choosing the users with disclosed phone numbers and saving their data in specified lists
5. Sending the message using API id and access hash
Two remaining chunks are dedicated to keeping the data of targeted users in the XLS files using the
xlsxwrite package. The second chunk contains the code for saving all the usernames (if they exist) inside
the XLS files, yet the third chunk is responsible for keeping the phone numbers of users who got the
message.

Already scraped groups: 10 (2 were testing cases)
Amount of people who received: 50-60
Amount of people who have hidden afterward: 25-30
