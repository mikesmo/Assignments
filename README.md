# Assignments

## Assignment 1

You will earn €5 for this assignment. When you think you have finished, let me know and I will review whether the assingment has been completed or what more needs to be done.

**Goal: Install an Apache 2 web server on an EC2 server on Amazon Web Services**

1. Create a GitHub account using your gmail account (###.sydney@gmail.com).

https://github.com/

2. In Github create a public repository with a `Readme.md` file.

3. For all the following steps you need to create instructions for another student so that they are able to exactly repeat the steps you did to create the server. You need to write the instructions in `Markdown` (like this page). The instructions should have URL links for the student and commands for them to copy. For example:
```
$ cd myDirection
$ cp myfile.md
```

2. Create an Amazon AWS account. 

https://aws.amazon.com/console/
- When you need to enter a credit card, let me know and I will enter the details.

3. Launch an "EC2 Server" instance. 
- Operating System: Linux, Ubuntu.
- Size "Tiny" (free tier)

4. SSH onto the server. 

5. Install `Apache 2`

6. Create a simple web page `index.html` and host it on Apache web server. The contents of the web page will be:

```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
