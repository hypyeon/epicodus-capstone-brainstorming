# Capstone Brainstorming
by [Hayeong Pyeon](https://www.hayeong.website)

## Description
- This is a brainstorming section for Capstone project. 
- Draw.io was used for idea board & outline. (*Idea board created on Jan 12, 2024*)
- Application Planning #1 includes more in-depth plans about the app design and functionality, and what technologies to be used for major features. Came up with a name for this app - **Linkup Zone**. (*Completed on Feb 16, 2024*)
- Any in-person discussion regarding the project will be uploaded separately from the README, in `.txt` files, for recording and future reference purpose. 

## Idea Board (Jan 12, 2024)
![Idea Board](./src/images/drawio.jpg)
- This program is initially built for me and my family members who live in different countries with different time zones. 
- When this program is ready, we can communicate with each other without having to calculate their current, past, or future times in different time zones when trying to reach out to each other. 
- This program will also have an auto-send system that will have a message sent at a specific time of the receiver. For example, if I want a person residing in Korea to receive this message at 8AM their time, I can set their time for the receiving time then it'll automatically send the message at 3PM PST, without me having to calculate the time difference. 
- End goal for this program is to successfully apply software knowledge learned in Epicodus and to learn how to use Swift, the iOS app development tool. 
- Possible roadblocks: I have not developed an app that involves real-time messaging system or account set-up for users. 
- If I were asked to begin working on this program now, I would start with coming up with dashboard design on Figma and see what can be done with HTML, CSS, JavaScript and webpack. 

## Application Planning #1 (Feb 16, 2024)
![Figma Draft Design](./src/images/linkup-zone-figma.png)
- The application has 4 different menu sections: Time Zones, Contacts, Chat, and Settings. Time Zones and Chat sections will be priotized. 
- Technologies to be used: 
1. This project will be React-based. 
2. Messaging interfaces including displaying messages, input fields for typing messages, buttons, and other clock features will be built by creating components. 
3. `useState` and Redux will be used to keep track of the messages sent and received in each chat room. 
4. JavaScript's `Date` object will be used for current timestamp for sender's and receiver's time zones. 
5. Messages displayed will have information including sender's username, message content, and the timestamp. 
6. If time zone conversion is needed, `date-fns` will be used. 
7. In order to display real-time messages (without requiring users to refresh the page), **Firebase**, or other database technology will be used. 
8. **Jest** will be used to test out accuracy of messaging features including message contents and timestamps. 

## License
Copyright © 2024 Hayeong Pyeon | [MIT](/LICENSE.txt) 