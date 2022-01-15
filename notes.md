OPEN SOURCES GUIDE BY SIMON HOIJBERG
(https://github.com/aindrajaya/open-source-guide)
--------------------
CONTENT
"In real open-source, you have the right to control your own destiny - Linus Torvarlds"
--
0. Preface
The power of Open-Source is the power of the people. It's by far the strongest asset of the tech industry. In fact, I'm not aware of any other fields of work where sharing information and work openly is as highly prioritized and encouraged as it is in the tech world.
And not only that, it's also highly beneficial for the individual contributor. The takeaways from becoming an active contributor to Open-Source are huge - and potentially life-changing. In this book, I will highlight some of the many benefits of contributing to and running - Open Source Projects. When you are finished reading, you will have a clear understanding of what Open-Source is and why it's important. It will be especially clear how you can use Open-Source ot build a strong reputation, boost your career and help your business generate more revenue.
I will be sharing a nnumber of examples and case studies from some of the most prominent Open-Source contributors in the tech space. Additionally, I will provide with templates, Readme and other examples that you can appy direclty to your own Open-Source project.
--
1. What is Open-Source
When we use the term 'Open-Source' in the context of software development, we refer to projects which have their source code publicly available and which people can modify and share.
That means that anyone with interest can inspect, modify and enhance the source code that runs a piece of software. When a programmer improves an Open-Source software by adding a feature or fixing a bug, that programmer becomes a contributor to the project, and by virtue, a contributor to Open-Source. In most tech communities, being an Open-Source contributor is considered an honor.
--
# Why is Open-Source so important?
-- When technology meets the corporate world, ruthless competition and battle for proprietorship have a tendency to bury the principles that are supposed to let technology evolve: innovation, collaboration and exchange of ideas. Open-source projects celebrate an open exchange of ideas, collaborative, participation, transparency and community-oriented development. By allowing and inviting diverse perspectives, we ensure we are able to identify the best ideas.
We can solve problems that no one can solve alone, and we can implement standards that allow others to contribute in the future. When we reduce the interest in great software to its ability to efficiently solve a problem and gather support from the community, we end up with better solutions to our problems, founded on the best ideas out there.
Some of the most popular sofware projects out ther eare Open-Source. You've probably already heard about projects the Linux, Bitcoin, Tensorflow, Kubernetes, VSCode, Wordpress, React, Vue, and many, many more. So, explained simply: Open-Source helps technology evolve and the world become a better place.
Big words, I know.
And I wouldn't blame you for thinking, "Yes, Saving the world is great. Now, how can I personally benefit from open-source?". Keep reading. More on that in a little bit.
--
# What is Git?
-- Git is a version control system. It helps developers keep track of the stat of a codebase, thus making it convenient to collaborate.
In the same way that most programs allow you to save a file with the current state of whatever you are working on, Git allows you to take a snapshot of your current code and save that.
Every time you want to save new changes to a codebase, you make a 'commit', and Git will keep track of the full history of changes and store that in a hidden folder in your project. This allows you to "go back in time" and revisit changes that were done earlier.
Multiple developers can create their own 'branches' of this history and join these 'branches' back together in a 'merge', so changes from both branches end up being included in the same codebase.
[GAMBAR - ]
This concept is what makes Git such a great collaboration tool.
--
# What is GitHub?
-- GitHub is hosted platform where users can store code. It is built on top of Git, so it's also serves as the 'origin' of a Git repository. You can say that GitHub keeps the only "true" history and state of the codebase, which developers can clone and work on locally on their machines.
Typically, the collaborators of a codebase will upload - or 'push'- their commits periodically, and every time a collaborator wants to merge their branch of the history into this "true" history (a branch that's often called 'main' or 'master'), the will make a so-called 'Pull Request'.
A 'Pull Request' - or 'PR' - is a part of the tooling that GitHub provides. It enables other collaborators to review the changes that are introduced to the code before accepting it as a part of the codebase. Besides being a hosted platform for code, GitHub is also a social Platform. The social networking aspect of GitHub is probably the most powerful feature that GitHub has to offer. 
GitHub allows projects to be discovered easily, attracting other experts in the field, publicly discussing project revisions, thus allowing Open-Source projects to grow massively!
Each user on GitHub carries their own 'resume' showing your past contributions to other Open-Source projects. Building up a great GitHub 'resume' over time can become an extremely valuable asset for you as a software developer. Becoming an active contributor to Open-Source has never been easier or more convenient. When you are done reading this book, you should be fully equipped to make your first contribution on GitHub.
# Other Platforms
-- In this book, I will be focusing primarily on GitHub. However, there are other platforms that host code using Git, such as GitLab and BitBucket, and other online services that you can use to host code, such as Codepen and CodeSandbox, just ot name a few others.
--
====
2. How can you benefit from Open-Source
# Become a better developer
-- Maybe you are still entry-leve. Or maybe you are an experienced developer. No amtter the level, the world of tech is a place where you can (and should) strive to learn something new.
Open-source allows you to build up skills and become a better developer. If you are an entry-level or newly graduated junior, you may find yourself stuck in the famous "cannot get hired because I don' have experience" deadlock. Open-source doesn't require you to be hired, nor does it require you to have a degree or a resume. 
It's obvious opportunituy to grab some initial experience that you can show the recruiter for your next interview.
If you are an experienced developer, you may have gotten stuck in the ways at your current day job. You probably became really good at something very specific. Thus, your manager keeps placing the same old tasks on your table. Open-Source is the perfect place to pick up new skills that your current job doesn't allow.
Do you want to become better at Machine Learning? At blockchain? DEsign, UX, Organizing? there is always something to do in the world of Open-source. Don't wait around. Go and explore- and pick up a task that will make you become a better developer.
--
# Become a Great Collaborator
-- As a successful software engineer, you need to have great people skills. Your ability to work on a team and collaborate with other developers define your profile. Great collaboration skills outweight great techincal skills by far!. And believe me- recruiters and managers know this!.
If you are the person who can show and document great collaboration skills, you will be beating the math geniues and algorithm expert without good people skills any day of the week. Open-sources is a phenomical place to acquire great collaboration skills.
By the hear of any great Open-Source projects lies the collaborators' ability to communicate, resolve conflicts, discuss and exchange ideas, prioritize and delegate work and align approaches to push in the same direction. Not only will these skills make you stand out as an extraordinary software engineer, but they will also help open doors for future roles in management and leadership.
--
# Improve the Software you use
-- It's likely that you have installed a third-party library in the doftware you are building to later find out that there is a bug or gthat the functionality is too limiterd to your needs. The obvious community-minded approach here is to dig into the library and see if yo can patch it yourself. Dig in the source code, try to fix the bug or enhance the functionality. In this way, you can continue using the ibrary that you already shose for your project. And obviously- make a PR to the official library with your change! Not only will your own software get better, but you are also helping everyone else in the community.
--
# Grow your Reputation
-- When contribute to Open-source, you often end up meeting like-mined people with similar interests. Great collaboration forms bonds, and contributing to Open-source is something that most anyone in the community respects and acknowledges.
By definition, your contribution will be publicly available. They will also appear on your GitHub profile, and it will show that you are an active contributor to the Open-source community.
It's a great way to build up a strong reputation as a developer and build up a strong network of people that share your enthusiasm for software development. A network that can carry great opportunities and benefit you both on a professional level and in your private life.
[GAMBAR]
Above is an example of how GitHub shows your activity as an
Open-Source contributor. This GitHub profile belongs to Kent C. Dodds,
an author and Open-Source contributor behind a series of successful
projects.
--
# Attract Recruiters

====
3. How to Contribute to Open-Source Projects
# Finding good projects
# Preparation
# Contributing
# What's Next
# The first contribution

====
4. How to Start and Run an Open-Source Project
# Finding a problem to solve
# Creating a Solution
# Creating an outstanding Readme
# Creating a Contribution Guide
# Package and Publish
# Versioning
# Licensing
# Maintaining the Project
# GitHub's Communitiy Standards

====
5. How to Make Money on Open-Source Projects
# Make money directly with GitHub Sponsors
# Make money indirectly from Open-Source
# Use Open-Source to create leads for your product 