## Table of Contents

* [Communication channels](#communication-channels)
  * [GitHub Discussions](#github-discussions)
  * [Google Chat or Hangouts](#google-chat-or-hangouts)
  * [GitHub](#github)
  * [Email](#email) 
* [How to Ask Good Questions](#how-to-ask-good-questions)
  * [General guidelines to follow](#general-guidelines-to-follow) 
  * [Providing error information](#providing-error-information)
* [Building your skills: Technical writing](#building-your-skills-technical-writing)
* [Setup-related questions](#setup-related-questions)
  * [Before you ask a setup question](#before-you-ask-a-setup-question)
  * [How to ask a setup question](#how-to-ask-a-setup-question)
* [General questions](#general-questions)
  * [Before you ask a general question](#before-you-ask-a-general-question)
  * [How to ask a general question](#how-to-ask-a-general-question)
  * [Important points](#important-points)

Here we document Oppia's main communication channels and how to ask good questions.

## Communication channels

If you need help, there are a few communication channels you can use. Developers usually respond within 24 hours so long as you use a channel they actually check.

### GitHub Discussions

If you have questions regarding Oppia you can create a discussion here where Oppia's Welfare team and other developers will assist you in resolving the issue. You can create a discussion in any of the following categories based on the question:

* __Developer announcements__: Announcements for the Oppia developer community.
* __Q&A (multiple categories)__: Any questions that developers have.
* __General__: General discussions that don't fit in any of the other categories.

You can refer to [this guide](https://docs.github.com/en/discussions/quickstart#creating-a-new-discussion) on how to create a new discussion. You can also ping the welfare team by at-mentioning the welfare team: @oppia/web-welfare-team

### Google Chat or Hangouts

Most Oppia developers and teams use Google Chat or Google Hangouts as their primary means of communication, and they usually respond quickly.  However, invites often get lost in spam folders, and some developers use a non-public email address for Google Chat. You can ask your mentor to put you in touch with a developer if you don't know their address or if they haven't acted on your invite.

### GitHub

If you have a question about a pull request or issue, you can also reach out to developers by at-mentioning them (e.g. `@developer-username`) in a comment and assigning them to the issue. Be sure you both at-mention and assign them! Some developers only look at their GitHub notifications (which at-mentions trigger), while others only look at what they're assigned to.

You can even mention whole teams of people! For example, if you find an issue that is destabilizing the project, you could notify all the core maintainers by including `@oppia/core-maintainers` in your issue. The teams are all listed [here](https://github.com/orgs/oppia/teams).

### Email

We have several mailing lists in the form of Google Groups that you can join, but please note that these are less active than GitHub Discussions:

* [oppia-announce](https://groups.google.com/forum/#!forum/oppia-announce) is for announcements of new releases or blog posts. It's not for asking questions though.
* [oppia-dev](https://groups.google.com/forum/#!forum/oppia-dev) is the main mailing list for communication between developers and for technical questions. You can post to it even if you're not a member of the group. This is where you can ask questions, solicit feedback, or make developer-specific announcements (e.g. a temporary GitHub outage).

You can also email your mentor with any questions. If you don't have a mentor, complete the steps on the [[wiki page for contributing code to Oppia|Contributing-code-to-Oppia]] and we'll try to assign you.

## How to Ask Good Questions

At Oppia we don’t care how silly your question is! Just ensure your question is clear, and provide us with enough information to help us resolve it faster. 

### General guidelines to follow 

* __Be clear and concise__: Clearly articulate your question to avoid confusion and allow others to understand it easily.
* __Provide context__: If applicable, provide relevant background information to help others understand your question and situation.
* __Be respectful__: Maintain a respectful and courteous tone in your communication to foster a positive and inclusive community environment.
* __Format your text for easy reading__: Organize your question using paragraphs, bullet points, and appropriate formatting to enhance readability.
* __Proofread your message__: Take a moment to proofread your question to ensure clarity and accuracy before sending it.

### Providing error information 

When reporting an error, follow these steps to communicate the issue effectively:

* __Start with the command__: Rather than saying "I have an error," provide the actual command you ran. Copy and paste the command in your email or chat message to give recipients the complete context.
* __Include the specific error message__: Share the exact error message you encountered. This helps others quickly identify the potential cause and provide relevant solutions or suggestions.
* __Share reproduction steps__: Include the specific steps that recipients should follow to reproduce the error you encountered. This allows them to investigate the issue more effectively.
* __Explain your efforts and conclusions__: Explain what you've tried and what conclusions you've drawn, if any. (Providing a [[Debugging Docs|Debugging-Docs]] may help.)
* __Include relevant log lines__: Sometimes, log lines from the browser console or terminal can provide helpful context. However, ensure you only include relevant lines and omit unnecessary information to maintain the readability of the report.

## Building your skills: Technical writing

In addition to effective communication, developing strong technical writing skills can greatly benefit your contributions. We recommend exploring the technical writing courses available at https://developers.google.com/tech-writing/overview. These courses can help you improve your ability to write clear code comments, create technical documentation, and effectively communicate complex ideas.

## Setup-related questions

### Before you ask a setup question

1. You can setup/install Oppia by visiting [[this page|Installing-Oppia]].  Make sure you follow **all** the mentioned instructions from the beginning in a step-by-step manner.

2. Make sure each step succeeds (verify it with the expected behavior if mentioned in the wiki).

3. In case of any unexpected behavior/errors at any step, make sure you check out our wiki on [how to troubleshoot when you are facing installation errors](https://github.com/oppia/oppia/wiki/Issues-with-installation#when-you-encounter-an-installation-error).

If you are still not able to fix your error, start following the section below to raise your question on [GitHub Discussions](https://github.com/oppia/oppia/discussions/categories/setup-issues).

### How to ask a setup question

> [!NOTE]
> If you are stuck at Step X, we will assume all previous steps through X-1 were successful for you. In case there were any previously failed steps, kindly mention those too with their error logs.

Please follow the template given below (mark x inside checkboxes to tick them) for creating a GitHub Discussions.

```md
**Checklist**
- [ ]  I have followed the [Before you ask a setup question](https://github.com/oppia/oppia/wiki/Get-help#before-you-ask-a-setup-question) section of the wiki.

**System Information**
- OS: (Be specific Ex: Ubuntu 20.04 or Ubuntu 20.04 VM on MacOS 11.2.1)

**Steps followed**

// If you encountered this error while following a wiki page, provide a link to the page and specify which step failed. Otherwise, list what steps caused the error. These should be detailed enough for someone else to follow them.

**Error log**

//paste error log here

or

paste a screenshot

**Approaches already used to resolve the issue**

(eg: Link to a Stack Overflow answer or any solution that you have tried)
- enter any additional description
```

## General questions

### Before you ask a general question

* We expect that you have already **set up Oppia on your machine**, and it is successfully running. (If not, kindly do that first!)
* Prepare a debugging doc following [[the guidelines provided on the wiki page|Debugging-Docs]].
* If there are **failing e2e tests** on your PR, and you haven’t done any changes in that direction, kindly understand that sometimes they just fail due to [flakiness](https://github.com/oppia/oppia/wiki/End-to-End-Tests#flakiness). You should request for a re-run of those only when it’s preventing your PR from getting merged.

### How to ask a general question

Follow the template below for asking questions (fill in the values inside {{}} brackets and mark x inside checkboxes to tick them) to leave a comment on a pull request. Adapt the template as needed if you are using another channel.

```md
@{{PR reviewer or Mentor username}} PTAL!

**Checklist**
- [ ] I have filled the [CLA](https://goo.gl/forms/AttNH80OV0) and the [Oppia Contributor Survey](https://goo.gl/forms/otv30JV3Ihv0dT3C3)
- [ ] I have setup Oppia locally (verified by running `python -m scripts.start`)
- [ ]  I have worked through the [Before you ask a setup question](https://github.com/oppia/oppia/wiki/Get-help#before-you-ask-a-setup-question) section of the wiki.

**System Information**
- OS: (Be specific Ex: Ubuntu 20.04)
- [ ] Virtual machine

**About the issue**
- {{Describe the problem}} (eg. Failing e2e tests: "The test has been
  failing repeatedly since {{x}} previous runs, and I haven’t done any
  changes related to it. Requesting a re-run.")

**Approaches already used to resolve the issue**

(eg: Link to a Stack Overflow answer or any solution that you have tried)
- #{{Link to the debugging doc}}
- enter any additional description
```

### Important points

* If you are unable to push changes due to some reason, you can create a [patch file](https://docs.gitlab.com/omnibus/development/creating-patches.html) and share it with the person you're asking for help.

* If you are facing issues in completing the assigned task, you can create a PR on your fork of the Oppia repository, troubleshoot your problem on that pull request with help from your mentor, and then create a new PR on the original Oppia repository.

* If you have not made a PR yet, because you are not sure:

  * what the issue is about, or
  * which files have to be modified, or
  * if your approach towards the solution is correct

  Then ask for help by commenting with your doubt/suggested approach on the issue page itself.  If you don’t get any response within **24 hours**, you can drop a message on [GitHub Discussions](https://github.com/oppia/oppia/discussions/categories/q-a-contacting-folks) too.

* If you want to have a discussion on your approach, but aren’t ready to make a PR yet, you can create a [public gist](https://gist.github.com/) and include the link to it in your question. It’s always better to see the code you are talking about!

* **Avoid asking for help from people via emails or direct messaging.** We encourage everyone to ask for help on a common channel so that whoever sees your query first can help you or guide you how to take your query forward.

  * Comment on the issue page or the PR if your question is very specific.

  * Use [GitHub Discussions](https://github.com/oppia/oppia/discussions) if your question is not issue-specific.
