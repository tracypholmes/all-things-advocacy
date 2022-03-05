# Hashi-Tributor 101: How to Contribute

## Abstract
Terraform sits at over 1,300 open issues, and as a newly hired apprentice engineer at HashiCorp, it was Tracy Holmes' job to help tackle some of these. From finding the right issues to understanding labels, community guidelines to making the first pull request, she roughed through the trenches to understand how to do this so you don't have to.

Join Tracy Holmes from HashiCorp in learning the process of contributing so you can be on your way to making your first PR! This talk will look at what it is like jumping headfirst into an open source project like Terraform, effective techniques for interacting with the community, how to determine what issues to work on, contributing guides, and managing notifications.

## [Transcript](https://www.hashicorp.com/resources/hashi-tributor-101-how-to-contribute-to-hashicorp-open-source)

This is "Hashi-tributor 101: How to Contribute." It is a beginner talk, so some of this stuff you might have heard before, but some of the stuff you might not have.

I am Tracy P. Holmes across the board: Github, Twitter, and if you can find me elsewhere on social media, let me know.

I work for a product called Terraform, in the Terraform Ecosystem team. How many of you found out about HashiCorp through Vagrant or Packer? When I started on Terraform, I was like, "Oh, that's the same company? I had no idea!" So you're not alone.

I am a career switcher. In tech years, I'm ancient. But I had an itch: I wanted to learn how to code. I come from a project manager/infrastructure/tech support/sysadmin background. That's Windows and UNIX. A little bit of documentation engineer thrown in.

But I wanted to learn how to code. I found out about women who code when I went back to Austin and fell in love with Ruby and the fact that there are 15 ways to approach a problem, and the puzzle can still be solved. I was like, "I can apply that to life, because I don't know what I'm doing right now!" That's how I got into coding.

I'm a people person, as evidenced by the client-facing types of things that I tend to do. So I wanted to jump into the open-source side of things.

I knew I wanted to work with the open-source stuff because I'm big on helping people. I used to teach math. I thought it was cool that I could provide things for people to improve upon, I guess you could say.

I thought my previous customer experience and the client-facing skills would prepare me, even though the world was new to me. It's like working in a restaurant. You're a server and it's the first Friday night by yourself and they throw you to the wolves. That's what open source ended up being like. Because I had no idea.

Being a customer, or a consumer, as well as someone that provides the service, we tend to be a little bit self-entitled at times because we want things done. And I understand that.

But, a lot of times, open-source people or maintainers are not being paid. This is their side job or something that they do for fun. Or they're like me. I absolutely love the Notion app, and I keep throwing ideas at stuff that I can't actually fix. But they're happy to get the feedback.

Communicating with the open-source community
How can you and I be effective at communicating with the community? There are a few guidelines here. We've got the README, we've got the Code of Conduct, and we've got the Contributing Guides, or Guidelines. You would think that most of these would be self-explanatory, because we're all nice people. We know how to treat people, except when we get mad.

Let's go look at what these are.

A README just tells you what the project does, why the project is useful. How can I get started? Who do I contact? Where do I go? And it's usually the first thing that you hit when you go to any project repo.

Code of Conduct pretty much tells you how to engage the community. It tries to provide an inclusive environment for all of us to collaborate in. And it tells you how to interact with everyone else.

The Contributing Guides tell you how to contribute to the project. That one was self-explanatory. But we'll talk about that one a little bit more later.

Contributing Guide
If you look at this screenshot of a GitHub repo page, can you tell where the Contributing Guide is? Or if you normally go to the repo, can you tell where the Contributing Guide is?

Not easily. And that was the problem. The README is the first thing that you see when you get up there. It's a markdown file. You scroll down, and it tells you everything you need to know about the project.

There's this little .github folder that no one ever likes to click in that's usually at the top of the repo, because it's technically a little hidden folder. That's your friend. That's your first-aid kit for your repo. It's going to hold all of your templates. It's going to hold your Contributing Guide, issue templates, Code of Conduct, org report template, that kind of thing.

This is what it looks like. With ours, specific to AWS, we have a folder that holds our bug report, our question template, and our issue template. We'll look at that a little bit more later. But as you can see, it tells you what the maintaining guide looks like, where to find support, and that's where our little Code of Conduct file is.

Contributors need not be coders
So, ready to work. "How do I do that, Tracy?" I didn't know, so I'm gonna tell you what I figured out.

There are different types of things you can work on. You don't necessarily have to do code to contribute. You can work on documentation. If you find a typo, if the code block is like 2 spaces off, fix it, submit a pull request. Because I probably won't see that typo.

Features. Like I said, I had an idea for the subheading for Notion, and a month later they're like, "Thank you for sending that. We implemented that." And I was screaming all over Twitter. Features are something that you can try.

Bugs are something you can try. We always find bugs, but a lot of times we don't want to talk about them, and if we do we don't really want to fix them.

If you don't write anything else down from this talk, please write this down: You do not have to code.

I will forget to italicize something. I'm going to forget to turn something red. I'm going to forget that my three backticks should have had an HCL beside it instead of a JS. Do that for us, because there are tons of things that we won't get to or that we just don't see.

From my own experience, I had to learn Go in the past year, and I used something called "Learn Go with tests," by Chris James. It is a work in progress. He will tell you to help.

I of course was like, "He would never accept a pull request from little ol' me, because I don't know what I'm doing." And I found where he forgot a period after something and he forgot a semicolon, and like 2 hours later he had merged it in.

"All right! I'll try something else." And about a month later I was like, "We should probably rearrange all these chapter headings, because this book is good, but I have no idea where the heck I am at any given point in time."

He was like, "That's a good idea. You should probably work on that." I was like, "Yes! All right, this guy listens. And he shouts you out on Twitter when he does."

So I threw something else in there. I was like, "Maybe we should reword that, because I'm new and I don't know what I'm doing. But if I'm following you; you know what you're doing. So we need to talk." And he said yes and he merged that.

Trust me; they like it. He has an idea, he's putting it on paper, or digital paper, but he just knows he wants to get the idea out there. He's not going to remember everything that he's typed. He's not going to always review it. If he does, 500,000 pairs of eyes are better than one.

Labels
Labels are the things that help you know what you want to work on. AWS I think has 174 labels. Every resource that you could think of that AWS decided to come up with at 3 o'clock in the morning when they took a bathroom break, we probably have it in the label list. Sorry, AWS, it's the truth.

But labels are just this: They help you organize things. If you know you want to work on documentation and you're not good with code, go click on documentation and find all of the things that need documentation fixes. If you know that you want a good first issue because you're kind of ready to code, go look for a good first issue or a help-wanted issue.

Our labels look like these. We like to color-code a lot in the Ecosystem. You'll see a lot of purples and blues; it's nice and calming. It doesn't prepare you for the scary thing that you are about to get into.

More about the "good first issues:" On the Ecosystem side, I have, I guess you could say, the privilege to have had my hand in 3 different providers. You might see my name in AWS, you might see my name on the Azure provider, and you might see my name on the GitHub provider.

Two of those are maintained by the company. One of those is not. If I do not get to your GitHub issue, do not beat me up. It takes a little time. If there are things that you can't find in our repo—admittedly sometimes the AWS things—we do have "help wanted" and "good first issues."

But sometimes they are more difficult if you don't know what AWS is about or you're not really familiar with how Terraform structures things. Azure has a lot of "help wanteds" that are focused around documentation. GitHub, I'm just going to put everything as "help wanted" because I need your help. I'm just going to let you know.

But if you can't find anything in our repo, you can do something like 24 pull requests, which happens every Christmas. You can do something like Hacktoberfest, which is a really good way to find open-source repos and find new stuff to work on.

And a lot of the things are usually easy. A lot of open-source projects out there don't have any documentation at all. So they want someone who is passionate about the project to help. And then you can also look on Twitter or in GitHub at the first timers-only repos.

What's the point of the Contributing Guide?
Let's talk more about that Contributing Guide. As I showed you, that little .github directory may not be the easiest to find, but it's the thing you need.

What are the Contributing Guides and Guidelines good for? For the owners, Contributing Guidelines are a way to communicate about how you should contribute. For the contributors, all of you wonderful people, the guidelines help you verify what you're submitting and make sure that you're submitting well-formed pull requests and opening useful issues.

But ultimately, for both owners and contributors, Contribution Guidelines save time and hassles caused by improperly created pull requests and/or the issues that have to be rejected and resubmitted. Make a note of that.

I can say the AWS provider has a very robust—that's a nice way of putting it—a very robust Contributing Guide that tells you pretty much exactly what you need to know.

If you follow those guidelines and you follow those checklists, 9 times out of 10 your stuff will get reviewed. That's not to say it will immediately get merged and/or accepted, but if you do all the right things, you have a better chance.

That's what it looks like if you all want to make a note of where to find it.

Templates
This the path to your first issue and/or pull request. This is what you need to ask yourself: I was using something and I found a bug. Do I know how to fix it, or do I just want to submit the issue and hope somebody else fixes it? Or have I seen an issue that I know how to fix?

The only thing that I ask, or one of the only things that I ask, is, if you are submitting an issue, please follow the templates. They are not there for UI or UX reasons, because to be honest they're pretty plain.

But anything that we ask you for, please give us that info. If it asks you for documentation or the log or the debug or the stack trace or anything, give it to us. Even if you do not want to. Because any time that you do not spend helping us will not let us help you. We're not doing it to be mean.

The other thing is, if you find an issue that you're pretty sure you can fix, check to see if anyone is assigned to it.

This is my first year, and when I started, I was an apprentice. Things would get assigned to me based on things that my boss or coworkers would decide that I could work on. In the past week, a very enthusiastic contributor has taken 3 of my assigned things. At first, of course, you think, "What is he doing? He's being mean for no reason at all."

Then you have to go, "I'll be an adult about this. This is someone that is probably new. They've gotten into a groove; they decided, 'I can do these things; let me do it.'"

So if you see someone assigned, or even if you don't, bop in and say "Look, I'm new. I really want to work on this. Has anyone grabbed it? If not, I'll grab it." That way no one will try to take it from you.

Because if you're in AWS and it's been 2 weeks that you've been working on these resources and they're brand new, and you get in and someone else has thrown in a PR at the same time as you, that not ought to be. I'd rather you not have to do double work or work that might not be appreciated.

If you go into the Contributing Guide, and you've never done a PR, we link you to ways to do it. A lot of those links will take you straight to GitHub Help and/or the GitHub Lab that will walk you through creating your first pull request, best practices, what you need to do, how to set up that branch, how to get that branch merged, that kind of thing.

The other thing about the Contributing Guide: If you scroll down, you will see that we have checkboxes. Use those checkboxes to make sure that you're hitting everything that you need to hit.

I really want your stuff to get merged. That's less stuff that I have to do. Let me rephrase that. That's less stuff that I have to do when I could focus on something else. That might be a better use of my time, because I'm still learning how to review things properly myself.

And that's what they look like. Issue templates and feature requests all have checkboxes.

The thing I wanted to point out is we require acceptance testing. That's not something that we're suggesting; we require acceptance testing. If you post those results, that will help us not have to go in the background and rerun tests. Especially if we're in a different environment, because we might not be able to reproduce whatever issues you are having.

There are plenty of issues to work on
The Terraform repo has over 1,100 issues as of this morning. And in some repos, like the providers repos, the AWS provider number keeps going up. I'll get to the why in a second. AWS has 2,100 issues as of this morning. I didn't check Google and Azure; they're not as high, but they still have more than they probably should.

When I started on AWS a year ago, we had 1,600. AWS is a very popular provider. Google Cloud provider is very popular. Azure is very popular. They're known as our Big 3. However, I need you all to know, big products do not equal big engineering teams. A lot of people forget HashiCorp is still considered a startup.

We just hit 600 employees, and I guarantee, not all of those are engineers. Packer and Vagrant, some of your favorite stuff, they have 2 engineers dedicated to them a piece. Imagine if someone has to take off for 2 weeks. Imagine if someone is not there. And you've got a full repo of issues and 1 person working on those issues.

AWS, Google, Azure, with those 2,100 issues and those 500 and 600 and 700 and 800 and 1,000 issues, we've routinely only had 1 or 2 engineers. And groups that are open source that are working on projects in their spare time, and it becomes popular, it's probably 1 person working on it after work, while they're trying to take care of the kids or that kind of thing.

So be respectful of the open-source projects that you want to contribute to, because you have no idea what it looks like on the other side or why they haven't responded immediately or why they haven't merged immediately.

You can probably go through our repo and find some of the less friendly contributors. But we're usually respectful about how we talk to them. We say, "Hey, I get it. But you also didn't give us all of the reproducible stuff that we needed in the first place."

Seeking help
What happens when you're stuck?

This is still a learning experience for me. As Terraform grows and changes or the company grows and changes, it's a learning experience for a lot of people. A lot of times we just don't know what's going on, and we've got to break it and patch it and try it and get feedback from you all before we know what's going to work.

Don't do like I did: decide to contribute and you don't know how and don't ask for help.

Max is not even my manager, and I blew his DMs up in Slack about, "I don't know how to ask this question. I feel so stupid. Why is no one helping me?"

We're a small team. Not everybody can reach out. If you don't raise your hand and ask for help, no one knows that you need help. And we have some really nice contributors, and there are avenues for asking for help that are not just on the World Wide Web.

We have things like discuss.hashicorp.com. We used to have 3 or 4 avenues that you could jump onto if you needed help from someone. We've cut the majority of those in favor of the community forum, which is still pretty new.

If I close your question, it's because I want you to go to the community forum and ask it. It's a good place to ask for help, and there's probably someone else that's trying to do that new resource or hit the same bug that you hit that didn't realize it was really a bug until you said something about it.

Another place to go is Reddit. Reddit has a pretty active Terraform subreddit. They also have a very active AWS subreddit. They get a little bit angry in there. But I understand.

Reddit is a good place for a lot of our products. Just go to the relevant subreddit, and that's it. And then Stack Exchange. Even if you don't want to talk in there, your answer is probably already there, and if you respond they're probably just going to jump down your throat anyway, so it doesn't really matter. Just take the answer and run.

And there are others, but whatever project you're contributing to will typically tell you how to find help.

The second thing that you definitely need to write down: You are not stupid. Things will not always go the way that you want them to, no matter how passionate you are about getting said thing done.

Like I said, I'm an olden tech career-switcher that, in her oldness, became an apprentice. I'm 39 years old. There's no way in the world that I would think that I would have the word "apprentice" in front of my name, knowing that I've got managerial skills and project management skills and senior this and senior that.

I decided I was bored one day and I did not like my life and, hey, I'm going to try this. Things happen. You're not stupid because they happen. You're just frustrated. Talk a walk, come back, ask someone for help. You'd be surprised what a new set of eyes will do for you.

What have we learned?
Read the friggin' documentation.

No contribution is too big or too small

Ask for help

And you're absolutely not stupid

Those are my basic takeaways.

About contributions: I absolutely love the space I'm in. I love my team. I love the people I get to talk to every day. They will be the first to tell you, "Tracy, I saw that 2 weeks ago, and I totally forgot that I needed a period, and I needed to take that data source and rename it as a resource, and I copy-pasted the wrong thing. Thank you for fixing that." That's something else that someone else doesn't have to do that I can do.

Like I said: documentation, bug fixes, features—try it. If you don't try it, you don't know if it's right or wrong.

We are hiring. This is not a recruiting effort.

If you find that you like contributing so much, try it. If you don't apply for it, you never know if you'll get it. Because I never thought I'd be up here a year ago.

And that's it. You all are a very enjoyable crowd. Thank you for listening to me. I appreciate that.
