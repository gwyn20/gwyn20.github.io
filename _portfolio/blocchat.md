---
layout: post
title: Bloc Chat
thumbnail-path: "img/blocchat.png"
short-description: A Chat Room Application using Firebase.

---

{:.center}
![]({{ site.baseurl }}/img/blocchat.png)

## Explanation

Bloc Chat is a responsive Chat Room application which sends and receives messages in real time using AngularJS and Firebase.

## Problem

A site needed to be built where the user could view a list of available chat rooms, set a user name and send messages associated with their username as well as have the ability to create new chat rooms.

## Solution

The site was built with Angular JS and uses the Firebase service to control the messages and rooms.

## Results

The end result is a simple yet clean Chat Room application which allows the user to set their username and view or create a new chat room where they can send messages and view responses in real time.

When the user first accesses the site they are presented with a modal which asks them to create a username.  If the user does not create a username they will be unable to proceed to the list of chat rooms.

{:.center}
![]({{ site.baseurl }}/img/blocchat2.png)

Once the user has registered their username they are able to view and select a current chatroom or create a new one and send messages.

Each message is then displayed on the right with the username and time/date of entry.

## Conclusion

Building the site with AngularJS and Firebase provides a powerful single page application. The added use of Modals allows users to interact with the application in a seamless manor.

{:.center}
![]({{ site.baseurl }}/img/blocchatiphone.png)
