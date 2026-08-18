# Version Control

Fundamentally, [version control](https://en.wikipedia.org/wiki/Version_control) is the practice of tracking edits made to computer files over time. A Version Control System (VCS) is a software tool that automates some aspects of version control.

One example of automated version control is Microsoft Word's Track Changes feature, which lets you make pending changes to a document that can be accepted or rejected by your collaborators later.

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/4167d2e7-9451-471a-b9c5-efeb58902db9" />
</div>
<br />

Other tools like OneDrive's Version History feature can be used to find out what text a document contained at a previous point in time, as well as what changed from that version to the next, and who changed it.

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/1fb7a97c-e6cd-4570-9ba0-857b39a12679" />
</div>
<br />

Today we will be learning how to use [`git`](https://git-scm.com/), which is a software tool that automates some aspects of version control. `git` was originally designed to make it easier for a large group of people to collaborate on a programming project over the internet. It is particularly useful for resolving differences between files caused by multiple people making conflicting edits to the same file.

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/5f050c7d-0809-4530-87b6-283eb3ed505b" />
</div>
<br />

While `git` was created as a tool for people who make software, it is general-purpose enough that it can be used to keep track of changes to many different types of files, and you don't need to know how to code to use it effectively.

## Advantages of Using a VCS

Keeping code or documents under version control can make it much easier to answer questions like:

* Who changed this?
* When did they change it?
* Why did they change it?
* How is it different from what it was before?

<br />
<div align="center">
  <img width="700" src="https://github.com/user-attachments/assets/00964e13-f5e3-4f87-af4a-532b761f767c" />
</div>
<br />

For example, when you make a change and track it with `git`, you have to write a short message to go along with it. Ideally, you and your collaborators should use this to provide a clear and concise reasoning for each change you make. This can be extremely helpful when revisiting a project after a period of time focusing on other things.
