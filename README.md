# The Flipped Interview Model

## What's This About
The Flipped Interview is a different way of approaching the interview portion of recruitment. It's based on the [Flipped Classroom](https://en.wikipedia.org/wiki/Flipped_classroom) model that's been successfully used in education.

In traditional education, each class period will be primarily spent on a lecture from an instructor. At the end, the instructor might give out an assignment to complete before the next class period.

In a Flipped Classroom, an instructor provides the learning and research materials prior to class. Students are expected to have reviewed the materials and done any pre-reading prior to meeting. Then, instead of a class period being used primarily for lecture, the face-to-face time is used for discussion, project work, collaboration, and other activities that benefit from being in the same place and time.

The Flipped Interview attempts to apply that type of change to the interview process. In a traditional interview, a candidate comes to the potential employer and meets with one or more representatives of the company. The interviewers ask the candidate a series of questions, record the answers, and compare notes at the end. If it's a technical interview sometimes they will ask the candidate to write pseudocode on a whiteboard or document their thought process around a particular topic.

A Flipped Interview moves all the question/answer and capability demonstration to an asynchronous process. The candidate receives all of the questions in the interview ahead of time, and can review and write their responses prior to the interview. The interview itself is spent reviewing those answers together, or other activities that are more valuable in a face-to-face environment.

This repo describes why you might want to implement this model and how I envision this process working. I should mention that as a hiring manager I've implemented parts of this in my own interview processes, but I have not had a chance to use this process as it's described here. If you're interested in trying it, do connect with me on email at jwrubel (at) gmail dot com or on [twitter](https://twitter.com/jameswrubel) if you use that network.

My [slide deck](https://www.beautiful.ai/deck/-LBBNBKF5JwsC5q8VSrv/So-what-do-you-do-in-your-spare-time) for [Erie Day of Code 2018](https://eriedayofcode.com/) also talks about the flipped interview model.

I should also point out that while I'm a hiring manager and I try to stay up on best practices, it's definitely possible that organizations are using some variant of this process and I just don't know about it. Maybe this is already common practice! If you've tried this already, I would _love_ to know how it works for you. Let [me know](#getting-involved) what you think!

This project is [licensed](LICENSE.md) under the GNU Free Documentation License so you should feel free to contribute changes or adapt it to your specific needs, if you decide to try it. Not sure what that means? See [tl;dr legal](https://tldrlegal.com/license/gnu-free-documentation-license) for an overview of the license terms in plain English.

Want to help out? Want to suggest an improvement or just yell at the author? See the [Getting Involved](#getting-involved) section for more ways you can do so.

## Why
Most hiring processes don't work well because we focus a lot of attention on how to take an interview well but provide almost [no support for managers](https://www.interviewedge.com/articles/The-Flawed-Interview-Process.htm) to learn how to conduct one well. Hiring processes also expose [organizational biases](https://hbr.org/2017/06/7-practical-ways-to-reduce-bias-in-your-hiring-process).Personally, as a candidate I find that interviews where questions are not known in advance cause me incredible stress. I'm the type of person who loves to be prepared, and if I don't know what to be prepared _for_ I tend to get extremely anxious and distracted, which greatly affects my interview performance.

It's also worth noting that this process would work _really_ well for remote teams and organizations, since it seeks to minimize the overhead and expense of meeting in person.

I should point out that the Flipped Interview concept isn't entirely new - There are plenty of [articles](https://hbr.org/2013/11/when-hiring-first-test-and-then-interview) that describe the benefit of giving candidates up-front tests, and personally I know of many companies who ask candidates to work offline on a project and submit it for feedback. The piece that I think is rare is actually moving the entire question and answer process asynchronous. I've not seen any organization take it to this level, and that's why this knowledge base and article exists.

## How
This section describes how I envision the process of implementing Flipped Interview.

### Preparation
Before you begin screening or even post a job, it's important that your interviewers - the people who'll be reviewing candidate submissions - understand both the questions you'll be asking and the criteria for evaluating them.

You'll need to produce a list of questions that are the same for every candidate. If it makes sense for the position, you can put together a skills test like a coding exercise or a design problem (or use a product that offers these).

You might consider using a service like [Textio](https://textio.com/) to screen your job posting and questions for bias. You might consider translating your questions to other languages if your process can support non-native speakers.

It's more important here that the organization agrees on the questions and the process than the actual questions you use.

Also important: consult your HR office. They may be reluctant at first; that's natural, because change in a business setting means risk. But you'll want them on your side and involved. Try to emphasize that you aren't changing _what's_ asked, just _how_ it's asked.

### Screening
In a normal interview process you'd use a short phone screen to speak with candidates whose résumés look strong. It's used as a mini-interview; usually you ask for the person to walk through their résumé and talk about the company and the position. The risk here is even at this stage you're already making decisions about candidates, and you may be unintentionally forming biases.

In a Flipped Interview your goal here is to explain the interview process. If more organizations used this type of interview model, maybe this step wouldn't be necessary. But here you're trying to get logistics settled and explain both the process they'll be going through and what they can expect. This is also your chance to communicate your organization's values to the candidate, and to hopefully keep them engaged. The Flipped Interview is going to take more work on their part than a traditional interview, and you want to make sure that good candidates don't decide to take another offer just because the interview process was easier.

### Sending Questions
There are lots of ways to accomplish sending questions to a candidate for a Flipped Interview. At the most basic level you could just ask them to fill out a Google Doc. I've used a few applicant tracking systems, and I've seen some (like [greenhouse.io](https://greenhouse.io)) that include take-home tests in their interview process. but I don't know of any that specifically support this workflow.

There are also tools like [Coderpad](https://coderpad.io/demo), [Lytmus](https://www.lytmus.io/) and [TestDome](https://www.testdome.com/) that automate the process of code samples. Some of these are nice because they also provide sample projects, which saves you the time of having to think of them yourself.

Ideally I would want a system to combine both general/interpersonal questions and skills-specific tests in one web-based process, tied to the candidate profile in your recruiting software. When a candidate submits I'd want all of their responses checked for plagiarism too.  Once submitted I'd want each of my reviewers to get the submission and have a chance to review it based on response alone, using a rating system and evaluation criteria we all agree on.

### During the Interview
The goal of the interview itself is to get a chance to understand the candidate as a person and the thought processes behind their submissions. After all, given all interviews are by their nature different than the job itself, you're really evaluating how well a candidate's responses and thought processes will translate to being effective on the job.

In this process you'll spend however long the interview is reviewing the question and the candidate's response. Ask a lot of 'why' questions here. Another good leading question for discussion is, "what other options did you consider but decide not to include?". Finding out what a candidate didn't do is as important as seeing what they did do.

I highly recommend having all of your interviewers attend at the same time. It's more time-efficient, and it gives them all the same baseline of information to use when evaluating the candidate.

It's also worth noting that this process could also be conducted remotely through a virtual meeting, depending on the tools used.

As an outcome here, each interviewer should provide independent feedback on the candidate based on whatever you've established as a process. Personally I think it's important that interviewers not discuss candidates with each other prior to submitting feedback.

### Follow up
Hopefully as a result of this process you've got an objective ranking of candidates that you can use for making a decision. Hopefully this process was also more inclusive, and candidates from diverse or under-represented groups are better able to present themselves as candidates.

If you don't find this to be the outcome, I'd be interested [to know](#getting-involved) what's missing. One side benefit of having candidate questions and responses all written down is that you can go back and review later, instead of having to take notes during the interview.

The process of hiring is still more art than science. The stakes are so high as a hiring manager - if you get this wrong not only are you setting the organization back, but firing someone can be life-changing. Hopefully this process resonates with you and helps you make better hires.

## TODO
A couple of thoughts I had while writing this summary about things that would be work exploring.

1. It would be really good to convert this to Github Pages with some HTML. That wouldn't change the content of course but since the audience for this is a combination of technical and HR staff, HTML/Github pages might make this more approachable to both groups.

2. I haven't looked closely at various SaaS recruiting tools like Greenhouse, Lever, Workday, Jazz, Google Hire, etc to see if they could be adapted to work with this model. I know many of them can do pre-interview surveys, so it would be interesting to do a 'reference implementation' of the Flipped Interview model in each tool, just to see how well it works in practice.

## Getting involved
* Questions? Feedback? Please do @ me. Email: jwrubel (at) gmail dot com or  [twitter](https://twitter.com/jameswrubel).
- Want to suggest a change? Pull Requests are very welcome. If you are not a github user please contact me and I'll be happy to help review and incorporate your change in whatever method makes the most sense. Please note the project [license](LICENSE.md) however before submitting.

## Credits
I'd like to give credit to [Rob Wierzbowski](https://twitter.com/jameswrubel/status/931615803627200512) for the original inspiration to write down what had been in my head for a while, and to [Erie Day of Code](https://eriedayofcode.com/) for allowing me to develop and give a presentation on this topic.
