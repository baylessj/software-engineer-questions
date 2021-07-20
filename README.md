# Software Engineer

Hello, and welcome from the Syniti Engineering Team!

Thank you for your interest in joining Syniti, we're working on some
interesting and challenging problems and are looking for engineers with a
growth mindset to join our team. Our interview process helps us learn about
you as a person and at a technical level. But it's just as important that you
learn about us, our work, and our expectations so you know what you're
getting into. We foster a work environment where we are all comfortable and
love coming to work each day. We don't hire lightly and expect everyone to
contribute on day one.

Let's get started!

Please clone or download this repo and use it for the exercises described below.
Once completed you may either send us the URL to your git repo or a zip of
the folder.

We have four questions that we like to ask to get a sense of who you are, 
followed by a coding question we use to understand your technical strengths. 
You can write your responses to the first four questions directly in the README 
or as a separate file.

In answering the code question, please submit code as if you intended to
ship it to production. The details matter. Tests are expected, as is
well-written, simple, idiomatic code. While there are many libraries you
could use, we're expecting to mostly see code that you write yourself. Please
only use critical libraries for common functionality, such as parsing JSON or
writing tests.

We'd recommend you use whatever language you feel strongest in. It doesn't have
to be one we use (mostly Go and JavaScript) — we believe good engineers can be 
productive in any language.

Here are the questions, good luck!

1. What’s your proudest achievement? It can be a personal project or something
   you’ve worked on professionally. Just a short paragraph is fine, but I’d
   love to know why you’re proud of it.
   
I led Purdue's VEX U Robotics team to the undefeted first seed at the World Championships in my Senior year of college. We unfortunately lost in an upset in the quarterfinals, but the success that year caused a significant increase in our team's recruiting for the future years. I did my best to set the program up for success after I left, and they have won and placed as the runner up in the two world championships since I graduated.

2. What's a personal project you're currently working on? This could be a
   coding side project, hobby, or otherwise real world project you're working
   on.
   
I am currently spending my evenings and weekends hacking on [auToDo](https://github.com/autodo-app/autodo). It's my testing ground for a lot of web technologies that I want to learn while also being a functional product that helps me keep track of my car maintenance.

3. Tell us about a technical book or article you read recently, why you liked
   it, and why we should read it.
   
I recently read _Rework_ by Jason Fried and David Heinemeier Hansson, the founders of Basecamp. It was a neat set of observations about their experience creating a startup condensed in a small book. I wrote a full review of the book on [my blog](https://jonathanbayless.com/2021/02/08/rework.html).

4. Tell us about one of your favorite products (physical or software) and one
   specific aspect that makes it truly great.
   
The product I use most is my Gergoplex mechanical keyboard. It's a joy to type on and has made it painless to write code all day. I purchased the kit from its designer and assembled, soldered, and programmed it myself. Using the Miryoku layout on it allows me to access a full keyboard's set of keys with just 36 keys and little movement from home row. Like Rework, I have a full review on [my blog](https://jonathanbayless.com/2020/10/07/gergoplex-review.html). Fun fact - that article beat out CNET for the featured article spot in the google results for "gergoplex review"!

5. In this repo is a `data.json` file. It contains an imaginary example set
   of data a customer might need to migrate from one system to another. It's a
   JSON encoded array of objects. The customer understands some of the data
   might be bad and wants to know which records are invalid so they can ensure
   the new system will only have valid data. Write a program that will read
   in the data and mark any records:

   1. That are a duplicate of another record
   2. `name` field is null, missing, or blank
   3. `address` field is null, missing, or blank
   4. `zip` is null, missing, or an invalid U.S. zipcode

   Each record has an ID but that should only be used to identify a record,
   not for validity or duplication testing (eg, two records may be identical
   but have different IDs).

The output of the program should list the IDs of each invalid or duplicate
record, one per line. In the case of duplicates, mark both.

Example:

```
123ba
439a2
99abc
bac34
```

If you have any questions about the coding questions, please let us know.
