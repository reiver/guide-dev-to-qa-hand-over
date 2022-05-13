# GUIDE: Dev-to-QA Hand-Over

by [Charles Iliya Krempeaux](http://changelog.ca/)

---

A guide on what to do and what to not do when software developers hand-over their work to QA for testing and acceptance.

## Developer “Done”

A software developer's work often gets broken down into **tasks**.

Software developers, especially software developers earlier in the careers, often say a **task** is _“done”_ when they believe their programming work is completed.

These software developers are wrong!
An **task** isn't _“done”_ until it has passed QA, is accepted for release, and is deployed to the production environment, and works.

## Milestones

Sometimes just a single **task** can go to production.
Sometimes multiple **tasks** need to be completed, pass QA, and be accepted for release, before they can go to production (together).

Keeping things simple — whatever that minimum unit is that could get pushed to the production deployment environment (whether s single **task**, or a set of multiple **tasks**) that minimum unit is called a **milestone**.

## Prescribed

When a **milestone** is believed to have its programming work “done”, the next thing that should happen is this ⁠—

### №1:

The software developer who worked on the **milestone** should meet with whomever will be QA'ing the **milestone**.

That software developer should ask someone for the meeting.
Don't wait for someone else to get the meeting to happen.

But make sure to also include anyone else, in the meeting, who is relevant.

### №2:

A software developer who worked on the **milestone** (or a technical-lead / technical-director, production person, etc) should describe to everyone at the meeting what the **milestone** is about.

Don't assume others know anything about it.
Take a “EL5” (i.e., “explain it to me like I am 5 years old”) approach to it.

### №3:

The software developers who worked on the **milestone** should demo the **milestone** for the QA person (or people), and everyone else invited to the meeting.

It should be obvious which specific **task** each software developer worked on.

And it should also be obvious if a particular software developer has nothing to show. 

Encourage people to ask questions during the demo.

### №4:

The QA person or people should now engage in testing while everyone else is there to watch, and to help out if need be.

Any **problems** that are discovered should be recorded in whatever TODO list (software?) is being used.

### №5:

The **problems** should be prioritized.

The top **problems** should be assigned to the software developers to fix them.

### №6:

All these people should meet at least once a day to repeat this process until all the **problems** have been fixed.
