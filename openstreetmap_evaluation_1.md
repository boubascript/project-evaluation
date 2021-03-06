**Project Name**: [OpenStreetMapl](https://wiki.openstreetmap.org/wiki/Main_Page) -- [OpenStreetMap data to PostgreSQL converter](https://github.com/openstreetmap/osm2pgsql)

---

**Evaluating Person or Team**: Liulan Zheng, ChiShing Lee


---


### License

1. What is the project's license?
   - **In most repositories there will be a file named LICENSE or something similar in the root level of the repository. This is the one to examine. There may be different licenses on specific files, but the project will have a main license.**
---

### Code Base


1. What is the primary programming language in the project?
    - **The primary programming language in the project is C++**

1. What is the development environment? For example, is it Gnu C++ on Linux?
Are there instructions for how to download, build, and install?
    - **For macOS you can download it in [Homebrew](https://brew.sh/)**
    - **For windows there is unofficial build available from [Appveyor](https://ci.appveyor.com/project/openstreetmap/osm2pgsql/history) or [OpenStreetMap Dev server](https://lonvia.dev.openstreetmap.org/osm2pgsql-winbuild/releases/)**
    - **Most Linux distributions are already include osm2pgsql**
    - **There are [Installing](https://github.com/openstreetmap/osm2pgsql#installing) and [Building](https://github.com/openstreetmap/osm2pgsql#building) instructions in the README file**

1. Does the project depend on external additional software modules such as
database,  graphics, web development, or other libraries?
    - **Yes, there are servals external additional libraries that osm2pgsql uses locate at the [contrib](https://github.com/openstreetmap/osm2pgsql/tree/master/contrib) folder in the repository.**


1. Is the code easy to understand? Browse some source code files and make
a judgment based on your random sample.
    - **90% of the codes are written in proficient C++ database style, which is complicated for beginner**

1. Is this a big project? If you can, find out about how many lines of code
are in it, perhaps on [OpenHub](https://www.openhub.net/).
    - **This is a small project, it only has 16.k lines of code.**

1. Does the repository have tests?
    - **Yes, there is a [test](https://github.com/openstreetmap/osm2pgsql/tree/master/tests) that stores all the tests code of the project.**


---

### Code and Design Documentation
1. Is there clear documentation in the code itself?
    - **The contributors provide insufficient and lack of documentation in the code itself.**

1. Is there documentation about the design?
    - **They don't have any documentation about the design, however they have a list of [features](https://github.com/openstreetmap/osm2pgsql#features) about the design.**


---


### Activity Level


1. How many commits have been made in the past week?
    - **There have been five commits made in the past week**

1. When was the most recent commit?
    - **The most recent commit was made on February 28, 2020.**

1. How many issues are currently open?
    - **52 issues are currently open**

1. How long do issues stay open?
Take the five most recently closed issues and look at when each was first reported.
Compute the number of days that each was open and take the average.
    - **Since most of the recently closed issues are relating to the errors in code, the average of the five most recently closed issues are 5 days.**

1. Is there active discussion on the issues?
Read the conversations from some open and some closed issues.
    - **Yes, the people in the community reply quickly with links and suggestions.**

1. Are issues tagged as easy, hard, for beginners, etc.?
    - **No, most of the issues were not tagged**

1. How many issues were closed in the past six months?
    - **There are 25 issues that were closed in the past six months.**


1. Is there information about how many people are maintaining the project?
    - **Only three people currently maintain the project.**

1. How many contributors has the project had in the past six months?
    - **There are 7 contributors who have the project in the past six months, including one core contributor, one non-core contributor, and 5 new contributors.**


1. How many open pull requests are there?
    - **There are only two open pull requests remaining.**

1. Do pull requests remain un-answered for a long time?
Look at the closed pull requests to see how long they stayed open.
Take the five most recently closed ones and look at when each was first reported.
Compute the number of days that each was open and take the average.
    - **The maintainers answered pull requests very quickly. Some were merged within a couple of hours, and some of them stayed open for 2 days. Overall, the average time for a pull request to stay open is around 1 day.**
    
1. Is there active discussion on the pull requests? Use the same method as you did for the issues.
    - **According to Open Hub, this project has high activity, yet there are only 7 current contributors. There’s not that many replies under each pull request: some has none, where the maintainer just merges the pull request without replying, some has one or two because the contributor has to points out the errors in the code.**
    
1. How many pull requests were opened within the past six months?
    - **In the past six months, at least 100 pull requests have been opened, and only two pull requests are waiting to be checked and merged.**


1. When was the last  pull request  merged?
    - **10 hours ago on 2/28/2020**

---
### Welcomeness and Community

1. Is there a CONTRIBUTING document? If so, how easy to read and understand is it?
Look through it and see if it is clear and thorough.
    - **There’s a [CONTRIBUTING document](https://github.com/openstreetmap/osm2pgsql/blob/master/CONTRIBUTING.md). It provides the link for code style, procedures to test the project, steps on how to fork and pull, and etc. It’s very clear for a new contributor to follow.**

1. Is there a CODE OF CONDUCT document? Does it have consequences for acts that
violate it?
    - **It’s not under the repository.**

1. Do the maintainers respond helpfully to questions in issues?
Are responses generally constructive?
Read the issue conversations.
    - **Most of the conversation is short, and there’s not that many of follow up questions. You can’t really tell if the comments are helpful or not because the conversation doesn’t continue. Whoever opened the issue didn’t reply back.**


1. Are people friendly in the issues, discussion forum, and chat?
    - **For the majority of the post is just a question, some suggestions, more questions, and some examples. It’s like a regular conversation. Since there’s not that many contributors, they are trying their best to answer or help with the issue.**

1. Do maintainers thank people for their contributions?
    - **Not really, since there are only those contributors who contribute all the time. For the most of the time, they just merged the pull request without replying.**
    
### Summary

Do you think this is a project to which it would be possible to contribute in the
course of a semester?

   **We picked this project in Open Street Map mainly is because it used C++ as the main programming language. After evaluating the project, we think it’s not a good project to contribute. First of all, it doesn’t have a CODE OF CONDUCT. Secondly, the community is very small, it’s always the same people who reply, open an issue, and submit a pull request. You can’t even tell if an issue is solved or not in the conversation because the contributors didn’t reply on whether or not the links or the advices were helpful or not. For example, when someone points out something or asks a question, others will share couple links and give advices, and that’s the end of the conversation. The issues were also not tagged, so it’s hard to classify the issues.**



Comments on Installation
---

   **I tried to follow the installation instructions. In order to test this project, I need to install 9 libraries. I tried to download couple libraries that was listed in README, and I was stuck because for some libraries I can't find the correct download pages. After skimming through the rest of the steps, it seems very complicated and confused. Therefore, I didn't get to install or run it.**
