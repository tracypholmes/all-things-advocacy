
# I Found the Thing and Would Love To Contribute...Now What?!

## Abstract

Contributing to an open source project can be a very intimidating experience, but there are many ways to help out without having the "World's Best Developer" trophy on your mantle! In this session, we will cover many different ways for contributing, as well as tips and examples of best practices to ensure your contribution will be accepted. From finding the right issues, understanding labels, community guidelines, to making my first pull request, I roughed through the trenches (in the snow, uphill both ways) to understand how to do this so you don't navigate it alone.  I would be honored if you accepted this pull request - let's discuss the process of contributing so you'll be on your way to making yours!

## Outline/Talking Points

- What it's like jumping headfirst into an Open Source project
    - Bit of background on me
        - In tech years, I'm ancient. But I developed an itch the last time I moved to Austin. I was that kid that always took things apart. We weren’t rich, so I also had to put them back together! Break/Fix comes naturally to me. I wanted to learn how to code.
    - Why I was drawn to OS projects once I realized I wanted to jump into the software engineering side of things
    - What I knew and what I thought I knew
        - I knew - I wanted to work on open source stuff because I’m big on helping people, and I thought it was cool providing things for people to use and/or improve upon.
        - I thought - my previous customer service and client facing skills would prepare me even though this world is new to me. You know, like a server on their first Friday night of working tables by themselves.
        - I had no idea.
- Interactions - How can I be effective at communicating with the community?
    - Community Guidelines can help with that!
        - What they are
        - Throwing on my maintainer hat for a sec! One of our cofounder (Mitchell) uses APPLE. If I translate that to OSS speak….
            - **Approach** - Make sure you let the contributor know you appreciate their raising an issue.
            - **Probe** - Ask more questions (or politely push back) if needed to get missing info
            - **Present** - Set realistic expectations - trust me. I get it. AWS will decide to release things while taking a 3AM trip to the bathroom. Microsoft will break the SDK, fix it on Friday, break the fix on Monday. Do what you can and let the users know.
            - **Listen** - OSS folk can be MEAN. Some on purpose, some just frustration (just like in regular customer service positions). We have an OSS Maintainers Slack for feedback/response review when that happens. Other companies may have something similar
            - **End** - Make sure you let the user/contributor know you appreciate their help and next steps! A smiley will go a long way….
            - It’s not that easy, but it is *easier* with guidelines! Okay, hat off.
        - Break things down a bit
            - README - A README is often the first thing a you see when visiting a repository.
                - What the project does
                - Why the project is useful
                - How users can get started with the project
                - Where users can get help with your project
                - Who maintains and contributes to the project
            - Code of Conduct - A code of conduct is there to protect everyone participating in a project as it defines standards for how to engage in a community. It signals an inclusive environment that respects all contributions. It also outlines procedures for addressing problems between members of your project's community.
            - Contributing Guide - Contributing guides are where all the guidelines on how to contribute are located!
            - Where do I find this stuff?!
                - The project's root directory!
                - Examples: [https://github.com/quii/learn-go-with-tests](https://github.com/quii/learn-go-with-tests) & (or in the .github folder) [https://github.com/hashicorp/terraform-provider-aws/tree/main/.github](https://github.com/hashicorp/terraform-provider-aws/tree/main/.github)
                    - If you're wondering what that `.github` folder is, the .github folder is a hidden folder that lives on the default branch. It can be home to community health files (like contributing guide, issue templates, & code of conduct), as well as templates.
- How to determine what to work on
    - Different types of things to work on
        - Documentation
            - Typos, screwed up code samples, missing code samples, or even suggestions are all good contributions.
        - Bugs
            - Filter not working properly? Example based coded not returning correct info? Let the maintainers know.
        - Features
            - Have an idea for formatting output? Really want a bit more detail while using app “x”? File that feature request. Even if they don’t agree, most time maintainers will let you know yes/no, what is needed, etc.
        
        <aside>
        💡 **For all of you that believe contributing is ONLY related to code - get that thought out of your head right now.**
        
        </aside>
        
        - While learning go, I made a pull request to the GH repo that held the source material. HE THANKED ME & it made my day! Engineers, authors, etc are so busy trying to help others, they don’t always catch mistakes.
    - Introducing LABELS 🙌🏾  (Yes, labels itch. But you’ll never remember the size if you rip it out! )
        - **GitHub Says:** Labels on GitHub help you organize and prioritize your work. You can apply labels to issues and pull requests to signify priority, category, or any other information you find useful.
        - How do you even KNOW how to navigate the labels!
            - You can find labels in the label drop down while looking at issues
        - What do the different labels mean
    - What issues are good for newbies
        - How to find newbie friendly labels
            - To attract new contributors, issues with labels that start with `good first issue` or `help wanted` are featured on the user dashboard, search, and topic pages.
        - What to do if you see nothing geared towards newbies
        - Examples of resources that are focused on helping people make their first PR
            - [HacktoberFest](https://hacktoberfest.digitalocean.com/)
            - [Open Source Friday](https://opensourcefriday.com/)
            - [First Timers Only](https://www.firsttimersonly.com/)
            - or even check out [24PullRequests](https://24pullrequests.com/) which usually happens in December, but also has links to other things
- Contributing Guides 👀
    - What exactly **is** a contributing guide
        - **GitHub Says:**
        - For the repository owner, contribution guidelines are a way to communicate how people should contribute.
        - For contributors, the guidelines help them verify that they're submitting well-formed pull requests and opening useful issues.
        - For both owners and contributors, contribution guidelines save time and hassle caused by improperly created pull requests or issues that have to be rejected and re-submitted.
        
        **Make note of this.**
        
        - We saw earlier where the Contributing Guide was for "Learn Go with Tests". In the AWS Provider repo we looked at, it actually *used*  to live in the `.github` directory we discussed. Now it lives in `docs`. We're going to walk through it a bit as it also works with the next section.
            - I use this repo as there are actual checkboxes in there. USE THOSE LISTS!
            - Before you can start working on things, make sure you get your development environment set up.
    - The path to your first PR
        - Ask yourself these questions🤔
            - Are you submitting an issue?
            - Are you submitting an issue AND a fix?
            - Or have you found an issue you’d like to fix…
        - There are generally three types of issues:
            - Bug reports
            - Feature Requests
            - Questions
            - Things needed and templates will vary depending on the project you are contributing to. But these are the usual suspects.
            - If you have found an issue you’d like to fix, PLEASE make sure no one is already assigned or is already working on it! If you don’t see anyone assigned, just add quick comment on the issue stating your desire or intent to work on it.
            - Yes! An issue by itself is STILL a contribution. Whether you’re providing a fix or not, make sure that if you are submitting an issue PLEASE follow any templates and make sure you fill out all corresponding info.
        - Pull Requests
            - We're going back to the AWS Provider for this one. I like this section because it tells you exactly what to expect. If you’ve never executed a Pull Request (or PR), GitHub has a good [help section](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) and [labs](https://guides.github.com/activities/hello-world/#:~:text=Pull%20Requests%20are%20the%20heart,merge%20them%20into%20their%20branch.&text=You%20can%20even%20open%20pull,repository%20and%20merge%20them%20yourself.) to help with stuff like this.
            - Ultimately, we all want to save the time and hassle caused by improperly created pull requests or issues that have to be rejected and re-submitted.
    - Seeking help when you're stuck
- Where you can find me!
    
    Again I am @tracypholmes on the interwebz. The header image is courtesy of #WOCinTech Chat. I will clean this page up a bit, so a few things may change (or I may move it to Notist or my website in the near future)!
