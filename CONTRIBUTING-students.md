<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-generate-toc again -->
**Table of Contents**

- [Contributing Guide for Students](#contributing-guide-for-students)
    - [Getting Started Early](#getting-started-early)
    - [Am I experienced enough?](#am-i-experienced-enough)
    - [Our Expectations From Students](#our-expectations-from-students)
    - [Default Instructions](#default-instructions)
        - [How to write a great Proposal](#how-to-write-a-great-proposal)
        - [Dividing your project](#dividing-your-project)
        - [How to estimate time needed for development](#how-to-estimate-time-needed-for-development)
        - [Final Proposal](#final-proposal)

<!-- markdown-toc end -->


# Contributing Guide for Students

## Getting Started Early

Experience shows that the best thing to help your application is to contact the
organization you want to work with early. For this you can introduce yourself on
the mailing list of the organization, maybe fix a small
bug.
[The Python Software Foundation Wiki](https://wiki.python.org/moin/SummerOfCode/2016#Students) lists
a few things you can do to get started in free and open source software.

## Am I experienced enough?

The answer is generally: **Yes**. We value creativity, intelligence and
enthusiasm above specific knowledge of the libraries or algorithms we use. We
think that an interested and motivated student who is willing to learn is more
valuable than anything else. The range of available projects should suit people
with different backgrounds. At the same time if you have experience using your
project of choice or one of it's dependencies (e.g. language) make sure to let
us know about that as
well.
[FLOSS manual](http://write.flossmanuals.net/gsocstudentguide/am-i-good-enough/)
gives a good overview of this part for GSoC.

## Our Expectations From Students

### During the application phase

**The tips listed here can help your application. They are not required**

Organizations usually favor students that show a regular communication with
possible mentors / organization until Google announces the accepted projects.

Establishing a regular communication is good for 2 reasons. It shows that you
are a reliable student and that you have good communication skills. Good
communication skills are an important part of GSoC since a student and mentor
can rarely meet in person.

### During the summer

**Communication**

- Write a short report for us every second week in a blog
- Commit early and commit often! Push to a public repository (e.g. github) so
  that we can see and review your work.
- Actively work on our project timeline and communicate with us during the
  community bonding period.
- Communicate every working day with your mentor. Preferably in public using the
  standard channels of your project.
- If there is a reason why you can't work or can't contact us on a regular basis
  please make us aware of this.
- If you don't communicate with us regularly we will fail you.

**Evaluations**

- Set a realistic goal for all evaluation deadlines. If you fail to meet your
  own goal we are more likely to fail you in the evaluations.
- Create at least one public commit that has been reviewed before each
  evaluation.
- Have at least one commit merged into the current development branch of your
  project at the end of the summer to pass the final evaluation.
- The last point is a hard requirement. Make sure that your time plan includes
  time for the review process.

## Default Instructions

**This is a general guide. Organizations can have different instructions and you
must follow their instructions**

Projects proposed by mentors are listed at our [ideas list][IL].

You are welcome to propose your own project. If you wish to do so, please
contact the organization you want to work with before you start writing your
proposal and explain your idea to them. If you choose to propose your own
project idea you will need to find a mentor for the project. **Proposals without
a mentor will not be considered.**

### How to write a great Proposal

Firstly, think about your choice of project carefully, you're going to be doing
it for a couple of months, so it's important that you choose something you're
going to enjoy. Once you've made your mind up:

1. Make sure you've thought about the project and understand what it entails.
2. Contact us early! The earlier you contact us the earlier you will be able to
   get feedback from us to improve your application.
3. Don't be afraid to come up with original solutions to the problem.
4. Don't be afraid to give us lots of detail about how you would approach the
   project.

Overall, your application should make us believe that you are capable of
completing the project and delivering the functionality to our users. If you
aren't sure about anything, get in touch with us, we're happy to advise you.

### Dividing your project

We require that all of our students have at least one commit in the development
branch of your project before the end of the summer. The best way to achieve
this is to divide your project into small self contained subprojects and plan to
merge at least one of them around the phase 2 evaluations. We also require you
to have at least one commit reviewed by your mentor before each evaluation, the
division of the project will help with this too. But don't worry about it we are
sure that you will create dozens if not hundreds of commits for your mentors
review over the summer.

During your summer you'll likely encounter bugs in your project or find code
that can be refactored to help you implement your ideas. You can also
immediately fix them and help us all out. This has several advantages. All your
pull request will only concentrate on specific features and are much better to
review. And you'll also get direct feedback from other developers and users
during the summer.

Since this is a hard requirement we as mentors will also have an eye on that and
check if your proposal incorporates it and also warn you ahead of time during
the summer if we see that you might not make it. Communicating with us on a
regular basis is vital for that, though.

### How to estimate time needed for development

To get experience with a code base we recommend you try to fix some
easy/beginner bug or refactor a piece of code that doesn't conform to the
current style guides. Look at the code that you want to change, check if it
follows our coding guidelines. Do some research on the API's you want to use,
plan what classes you will add and how their public API will look. Write down
your algorithms in pseudo code. The better your research is and the better you
plan ahead the easier it will be to judge how long a given task will take. For
your time estimates you should also consider that you can do less stuff during
exams and try to be a bit conservative. If you have never done anything like
GSoC before you will tend to underestimate the time to complete a task. We know
that giving these estimates is not easy and that also professionals have
problems with it. Having a good plan, knowing its weak and strong points will
help a lot.

### Final Proposal

Your final proposal must be submitted to [GSoC](summerofcode.withgoogle.com) as
a PDF file. Your proposal name should start with *[sub-org-name]* to make
identification easier for the mentors. To convert a draft that you have written
before into PDF you can use [Pandoc][Pandoc].

~~~
$ pandoc -f markdown -t pdf YYYY/proposals/your-name.md
~~~

[IL]: 2015/ideas-list.md
[issues]: https://github.com/numfocus/gsoc/issues
[GSoC]: http://summerofcode.withgoogle.com/
[ML]: organization/team.md
[Pandoc]: http://pandoc.org/
