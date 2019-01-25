---
layout: essay
type: essay
title: Dumb Questions DO Exist
# All dates must be YYYY-MM-DD format!
date: 2019-01-24
labels:
  - Stackoverflow
  - Self-Improvement
  - Questions
  - Software Engineering
---
<img class="ui medium right floated rounded image" src="../images/nostupidquestion.jpg">

## **To Ask or Not To Ask?**
Asking questions is something I'm sure you've been told on your first day at kindergarten and you're probably tired of hearing it because I'm sure your Biology 101 teacher just told you, "Don't hesistate to ask questions during the lecture!". As we all know, questions are a great thing! We can use it to get ourselves one step closer to answering what we don't know, but in the 21st century, we have an abundance of resources available on this beautiful invention we call the internet with approximately 7 billion people using it, most of the questions you have are probably answered somewhere on a forum. So do you really need to ask every question that comes to your mind? In a jiffy, no. To explain, let me use software engineering as an example. In software engineering, or in a more general term, programming, everyone comes into a problem when they're coding something for their class assignment or a personal project their working on and their first instinct is to google their problem and check the first few Stackoverflow, GeeksforGeeks, and Tutorials Point links. Now that's the easy part, but what is actually difficult is trying to obtain the correct information to solve the problem and for some reason you just can't get your answer from these first few links. So what to do now? Post my question on Stackoverflow right? You could, but just make sure it isn't a dumb question. A dumb question? I've been told that there are no such things as dumb questions! You'd be surprised at how possible it is to have a dumb question.

## **What in the World is a Dumb Question?**
A dumb question is a question posted by someone who gave no thought and effort to figuring it out by themselves. Since there was no thought put into solving the question themselves, most of the time these question are vague. 
```
Here's an example from Stackoverflow: 
How can I search for an array of integers in a bigger array of integers? I'm a beginner in Java and I have been trying to create this program for hours now but I have been facing nothing but hardships.
```
This person posted this question on Stackoverflow hoping to find a solution to his/her's problem but instead got no replies and four "downvotes." The reason being is beacuse the question isn't specific to where the poster's problem is. Does this person not know how to search for an array of integers inside of a larger array because they don't know the syntax to access an object in an object? Also what is the context of their problem? And another reason is that the question itself is a very basic issue for beginners and they even state it themselves that he/she is a beginner. This means that there must be a solution to this already posted somewhere in Stackoverflow or in any other programming forum.

## **What You Should Ask**
Now what makes a question smart is a question that makes the viewers actually think. In the previous example, it was a basic problem that doesn't require anyone to answer since it probably existed somewhere. A smart question is one that is very specific to its own issue and the person asking for assistance has already attempted in diagnosing the problem and is genuinly stuck.
```
Here's an example from Stackoverflow once again (link to question at the bottom of the page):
I have:

1) A client side app that has its own domain: http://client.com

2) A server side app that has a separate domain: http://server.com

Now,

the scenario is:

1) Opening http://client.com/home in the browser, which displays an HTML page.

2) http://client.com/home redirects to http://server.com/login

3) http://server.com/login stores a cookie 'auth' and sends a redirect instruction to http://client.com/welcome

Response:

Access-Control-Allow-Origin: *

Connection: keep-alive

Content-Length: 104

Content-Type: text/html; charset=utf-8

Date: Wed, 16 Jan 2019 10:47:11 GMT

Location: http://client.com/welcome

Set-Cookie: auth=1479da80-197c-11e9-ba74-59606594e2fb; Path=/

Vary: Accept

X-Powered-By: Express

4) The browser receives the response, which does contain the cookie 'auth'

5) The browser redirects itself to http://client.com/welcome

6) 'auth' cookie is sent to http://client.com/welcome

Request:

Cookie: auth=1479da80-197c-11e9-ba74-59606594e2fb

7) http://client.com/welcome returns HTML but does not return the cookie 'auth'

enter image description here

enter image description here

8) http://client.com/welcome makes an AJAX request to http://server.com/data (CORS enabled), but the cookie 'auth' is not sent

9) http://server.com/data doesn't recognize the user because there is no cookie

The client side is an angular app hosted by Node.js

Edit:

As suggested, I've added to the response of server.com:

Access-Control-Allow-Credentials: true

but nothing has been changed.

Relevant client side code:

const headerOptions = new HttpHeaders({
      'Content-Type': 'application/json', 'withCredentials': 'true', 'Access-Control-Allow-Origin': 'true', 'Access-Control-Allow-Credentials': 'true'
    });

this.httpClient.get<any>(this.baseUrl + "data", { headers: headerOptions }).subscribe((res) => {
```
This person is having issues with the website they are attempting to create and instead of just leaving the post at, "How to save cookies after redirecting a website?", they specifically write out the scenario of the whole problem and even number it to give the viewers a chronological order of what is going on. There is a "Response" section as well that tells the viewers what the website is responding with. And later as people interact to help, he/she even has this "Edit:" section that they update the responders with to allow the problem to be solved more effectively. This "Edit:" section can also help the new people viewing it be updated with what is going on, so they do not give solutions to the problem that was already given. 

## **Topping it Off**
Now that you know what makes a question dumb or smart, I hope you become more effective at solving your problems and asking questions. Remember that a solution to your problem exists if it's general, such as, syntax for a new programming language you're learning or how to search through an array. The only time you would need to post a question on a forum such as Stackoverflow is when its very specific like the example I showed in the smart question portion. But having a good question doesn't make it smart, what will make it smart is how you format it. Tell the viewers exactly what you're stuck on and what you did do diagnose it. This proves that you actually put some thought into it. Also, remember to put everything in chronological order beacuse it will only help solve your issue quicker and makes everyone's lives easier and make sure to interact with the people replying to your problem because teamwork makes the dream work!
