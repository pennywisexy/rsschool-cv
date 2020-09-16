# Alexander Snitko

---

> Hi, I am Alexander and I am the future owner of Google.

---

## Education

2014-2019 (expected)
: Belarusian National Technical University
**Faculty of Information Technology and Robotics,
industrial robots and robotic complexes**;

    *Minor: Awesomeology*

Experience
---------------

I worked for 3 months on assignment and was taken into the army.

Technical SKills
--------------------

Programming Languages
:   **first-lang:** Phyton (read a book and taught video tutorials).

:   **second-lang:** After learning python for a while, I switched to **JS**. I         began     to teach him and still teach him. I also got acquainted with **html** and **css**     in parallel.

Sample Code
--------------------

Example code of score for my social network in react:

    let store = {
      _state: {
        profilePage: {
          posts: [
            { id: 1, message: "Hi hi!!!" },
            { id: 2, message: "it's my first post." },
          ],
          newPostText: "ItSenior^)^)^)",
        },
    
        _callSubscriber() {
          console.log("state changed");
        },
    
        messagesPage: {
          dialogs: [
            { id: 1, name: "Kolyan" },
            { id: 2, name: "Morzh" },
            { id: 3, name: "Snikipiki" },
            { id: 4, name: "AGL" },
            { id: 5, name: "Miner" },
            { id: 6, name: "Foku" },
          ],
    
          messages: [
            { id: 1, message: "Hi hi!!!" },
            { id: 2, message: "Saaaaab bra" },
            { id: 3, message: "Yau" },
            { id: 4, message: "Yau" },
            { id: 5, message: "Yau" },
          ],
    
          newMessageBody: "",
            },
        },
    
          getState() {
            return this._state;
          },
        
          subscribe(observer) {
            this._callSubscriber = observer;
          },
        
          dispatch(action) {
            this._state.profilePage = profileReducer( this._state.profilePage, action );
            this._state.messagesPage = dialogsReducer( this._state.messagesPage, action );
            this._state.sidebar = sidebarReducer( this._state.sidebar, action );
            this._callSubscriber(this.getState);
          },
        };

About English
----------------------------------------

I learn English on my own, taking information from all the resources, such as videos, games, applications and communication on social networks.

Other information
----------------------------------------

I graduated from the BNTU Faculty of Information Technology and Robotics. I worked for 3 months on assignment and was taken into the army. Now I am learning javascript just because I like it. And I want to get into automated testing. Since I think this is an important stage in the software life cycle for the user and it is more interesting to me. My main qualities are energy and quick learning. And the main drawback is probably excessive emotionality. I love reading books and boxing, but lately all my free time is programming. My biggest and most rewarding achievement I think is serving in the army.

----

> <pennywisexy@gmail.com> • +375 (29) 830-30-30 • 23 years old\
> address - Minsk, Belarus