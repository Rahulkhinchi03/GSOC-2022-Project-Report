<p align="center">
  <img src="https://user-images.githubusercontent.com/71710042/189519219-e667737b-c236-4f20-9bf7-78bafe27450d.png">
</p>


# Project: "Automate Release Process of Checkstyle"

| **Student**      | Rahul  Khinchi                                                                                                                                        |
| :--------------- | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Organisation** | [Checkstyle](https://checkstyle.sourceforge.io/)                                                                                              |
| **Project Link**      | [Automate Release Process of Checkstyle](https://summerofcode.withgoogle.com/programs/2022/projects/nWt378bQ) |
| **Topic**       | Automation and Release Process   
| **Tech Stack**       | Java, Maven, Shell Scripting, Bash Scripting, CI, Git, GitHub Action and API, JUnit, Docker
| **GitHub**       | [@Rahulkhinchi03](https://github.com/Rahulkhinchi03)                                                                                                     |
| **LinkedIn**     | [Rahul Khinchi](https://www.linkedin.com/in/rahulkhinchi03/)                                                                                              |
| **Email**        | <a href="mailto:rahulkhinchirk7@gmail.com">rahulkhinchirk7@gmail.com</a>                                                                                         |
| **Twitter**      | [rahulkhinchi_7](https://twitter.com/rahulkhinchi_7)                                                                   |

# About Me
 I’m a Rising Junior pursuing my bachelor's in Computer Science & Engineering. I will be graduating in 2024. My aim is to become a T-Shaped Developer (Design, Develop, Test, Deploy). I am leading technical communities like GitHub Campus Expert, Microsoft Learn Student Ambassadors, and Google Developers Student Club.


# Special thanks to my mentor and community:

- Roman Ivanov [@Github](https://github.com/romani)

##### Also Big Thanks to Project Maintainers for helping with organizing things nicely!

- Nick Mancuso [@Github](https://github.com/nrmancuso)
- Richard [@Github](https://github.com/rnveach)

# Primary Goals of the Project

- Maintaining the project without the last human factor point.

## Project type: Infrastructure improvement 

In our project CI process is already set in code and everyone can see it and propose changes for it. But we still have the release process 80% automated; unfortunately, it depends on 1 person to do this. The release process takes a bit of time to complete that is why we have the release process set in "ones a month" but in reality, we are ready to release at any point of time from any commit, as our development process already implies this. The release process focuses on delivery detail to users rather than just bumping a version and sharing jars. So we focus on release note generation to share all details with users and share it at web hostings and social media. The release process requires a lot of actions from a certain person who has admin access to websites/hosts and other accounts to make a release.

The goal of this project is to finish automation to let any person with Read-Write access in GitHub do release by activation of CI execution. The release process should be in scripts/code of our repo(s) to let all see what is going on and even is required to release manually in case CI is experiencing downtime or any other problems.

Completion of this project will help us to increase the frequency of releases if required to make sure that users can receive the released version to use almost right after code changes are merged into the main code base. It will make a contribution to the project more attractive as it will be apparent that as soon as a code change is accepted you can use it in a project where you are experiencing problems with defects. The frequency of releases will be defined later on and probably be based on the severity of fixed defects, contributors can share with us how much they ok to wait for the release.

## A BRIEF OVERVIEW OF MY WORK

### Community Bonding Period

- Understanding the current release process.
- Explored releasenotes-builder, a checkstyle tool for generating all the needful things for release.
- Interacted with Mentor to understand the scope of the project.
- Worked on the skills needed for the Project.

### Sequence Diagram: [Scope.](https://github.com/checkstyle/contribution/blob/master/releasenotes-builder/diagrams.md)

# Work During GSoC coding period

## June 15 - July 30
- Automation of the creation of settings.xml - (https://github.com/checkstyle/checkstyle/pull/11743)
- Automation of the Twitter - (https://github.com/checkstyle/checkstyle/pull/11745)
- Automation of update of the releasenotes.xml - (https://github.com/checkstyle/checkstyle/pull/11750)
- Updateing GitHub Action for bump-license-year.sh - (https://github.com/checkstyle/checkstyle/pull/11971)
- Updateing releasenotes to use GitHub Pages execution - (https://github.com/checkstyle/checkstyle/pull/12009)
- Automating execution by Github action bump-license-year.sh - (https://github.com/checkstyle/contribution/pull/620) & (https://github.com/sevntu-checkstyle/sevntu.checkstyle/pull/892)
- releasenotes-builder: fail execution if multiple labels - (https://github.com/checkstyle/contribution/pull/627)
- Add -generateGitHubPage and - githubpostTemplate arguments - (https://github.com/checkstyle/contribution/pull/628)

#### PR for enchancement!
- releasenotes script generated empty commit - (https://github.com/checkstyle/checkstyle/pull/11845)
- prepare-settings.sh fails to create settings.xml - (https://github.com/checkstyle/checkstyle/pull/11785)
- deleted bump-license-year-in-all-projects.sh - (https://github.com/checkstyle/checkstyle/pull/11905)
- Remove -PublishXdocWithPush and -PublishXdoc command - (https://github.com/checkstyle/contribution/pull/618)

## August 1 - September 10th
- created Github action that does version bump and update milestone - (https://github.com/checkstyle/checkstyle/pull/11993)
- Reuse Plain text release notes from releasenotes-builder - (https://github.com/checkstyle/checkstyle/pull/12007)
- Adding CheckForVariable function to util.sh - (https://github.com/checkstyle/checkstyle/pull/12022)
- Enhancements for bump version action - (https://github.com/checkstyle/checkstyle/pull/12062)
- Github action: Release prepare - (https://github.com/checkstyle/checkstyle/pull/12085)
- Github action: Update Github milestone and upload '-all' jar - (https://github.com/checkstyle/checkstyle/pull/12094)
- Github action: Update sources with release notes - (https://github.com/checkstyle/checkstyle/pull/12097)
- Github action: Publish release notes outside - (https://github.com/checkstyle/checkstyle/pull/12107)
- Github action: Publish release notes Twitter - (https://github.com/checkstyle/checkstyle/pull/12110)
- Github Action: Update github.io - (https://github.com/checkstyle/checkstyle/pull/12118)
- Github action: GitHub Milestone and Upload Jar - (https://github.com/checkstyle/checkstyle/pull/12119)

#### PR for enchancement!
- tweet-releasenotes.sh should be able to work on start and finish release names - (https://github.com/checkstyle/checkstyle/pull/12069)
- update all shell scripts for release automation - (https://github.com/checkstyle/checkstyle/pull/12084)
- rename all release action to have 'R:' prefix in name - (https://github.com/checkstyle/checkstyle/pull/12117)
- rename update-sources.sh - (https://github.com/checkstyle/checkstyle/pull/12123)
- Minor changes in in shell scripts - (https://github.com/checkstyle/checkstyle/pull/12125)
- Github action Release prepare should validate presence of releasenotes.xml - (https://github.com/checkstyle/checkstyle/pull/12127)
- update publish Twit action to use secrets - (https://github.com/checkstyle/checkstyle/pull/12138)
- execution of 'R: Update github.io' with '10.3.3' faililng - (https://github.com/checkstyle/checkstyle/pull/12162)
- updates in Github actions - (https://github.com/checkstyle/checkstyle/pull/12166) & (https://github.com/checkstyle/checkstyle/pull/12167)
- failure to publish github release notes ' R: Publish GitHub IO - (https://github.com/checkstyle/checkstyle/pull/12178)
- releasenotes-builder: update Github template to be more compact - (https://github.com/checkstyle/contribution/pull/632)
- Disable execution of GitHub actions with cron in fork repositories - 
1. (https://github.com/checkstyle/checkstyle/pull/12176)
2. (https://github.com/checkstyle/contribution/pull/650)
3. (https://github.com/sevntu-checkstyle/checkstyle-samples/pull/42)
4. (https://github.com/sevntu-checkstyle/sevntu.checkstyle/pull/898)
- satelite projects should use latest checkstyle as soon at is appears in maven repo -
1. (https://github.com/checkstyle/contribution/pull/635)
2. (https://github.com/checkstyle/contribution/pull/636)
3. (https://github.com/checkstyle/contribution/pull/637)
4. (https://github.com/sevntu-checkstyle/checkstyle-samples/pull/39)
5. (https://github.com/sevntu-checkstyle/checkstyle-samples/pull/38)
6. (https://github.com/sevntu-checkstyle/checkstyle-samples/pull/37)
7. (https://github.com/sevntu-checkstyle/checkstyle-samples/pull/36)
8. (https://github.com/sevntu-checkstyle/sevntu.checkstyle/pull/896)
9. (https://github.com/sevntu-checkstyle/sevntu.checkstyle/pull/895)
10. (https://github.com/sevntu-checkstyle/sevntu.checkstyle/pull/894)


## PR's LEFT to complete!
- releasenotes-builder: update Github template - (https://github.com/checkstyle/contribution/pull/655)
- releasenotes-builder: avoid extra line wrapping - (https://github.com/checkstyle/contribution/pull/656)
- failure of update github.io to clone checkstyle.github.io - (https://github.com/checkstyle/checkstyle/pull/12174)
- releasenote-builder: should have execution mode to fail - (https://github.com/checkstyle/contribution/pull/651)
- releasenotes-builder: Release notes for GitHub shows escape at-symbol - (https://github.com/checkstyle/contribution/pull/653)


### My overall contribution to Checkstyle!

- [checkstyle/checkstyle](https://github.com/checkstyle/checkstyle/pulls?q=is%3Apr+is%3Amerged+author%3ARahulkhinchi03+)
- [checkstyle/contribution](https://github.com/checkstyle/contribution/pulls?q=is%3Apr+is%3Amerged+author%3ARahulkhinchi03+)
- [sevntu-checkstyle/checkstyle-samples](https://github.com/sevntu-checkstyle/checkstyle-samples/pulls?q=is%3Apr+is%3Amerged+author%3ARahulkhinchi03+)
- [sevntu-checkstyle/sevntu-checkstyle](https://github.com/sevntu-checkstyle/sevntu.checkstyle/pulls?q=is%3Apr+is%3Amerged+author%3ARahulkhinchi03+)
- [Issues](https://github.com/checkstyle/checkstyle/issues?q=is%3Aissue+author%3ARahulkhinchi03+)


#### Release Process: [BEFORE](https://github.com/checkstyle/checkstyle/wiki/How-to-make-a-release) and [AFTER](https://github.com/checkstyle/checkstyle/wiki/Semi-automated-release) Summer!

### Further steps:

- My experience with GSoC was great, and I plan on staying here and enjoying the open-source culture. I met some really good mentors and organizers. That being said, I think I got the essence of what GSoC was intended for. Opensource is my favorite way to do work!

###

### Thank you [Checkstyle](https://checkstyle.sourceforge.io/) for an amazing summer of code 2022!
