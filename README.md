# Using Notion to Stay Organised (My Notion Assignment Tracker)

**Updated December 2022**, [originally published](https://github.com/itsmeimtom/thomasr.me/blob/dff5a743e2bf7e3a6d95d16e39504fb217376fdd/_things/solcol.md) at ThomasR.me

---

One of the things I pride myself on is my ability to stay organised. To keep track of all [my assignments](https://github.com/tomatsolihull/assignments), I make use of [Notion](https://notion.so). Below follows a short overview of my page, hopefully it will be of inspiration to you.

I am writing this document while I am still studying, and it is my intention to keep it up to date as I progress. It is also my intention to create a similar system for my work at university, and I am looking forward to seeing how that may materialise.

## Quick Links

![A screenshot of Notion, showing five links under the heading 'Quick Links.'](https://user-images.githubusercontent.com/14424577/230742242-0f0ae3eb-7d5a-4da2-93ce-af75cc520f7a.jpg)
The top of the page has a selection of five frequently accessed links. _Outlook and Office_ is self-explanatory, but the others are a little more exciting. _ProPortal_ is used by the College for attendance tracking. Moodle is used for assignment submissions and is where work is uploaded, and feedback given. _Uniflow_ allows printing and _Student Hub_ is simply a link to the Intranet.

## The Assignment Tracker
![A Kanban board with six groups](https://user-images.githubusercontent.com/14424577/230742271-eb2d87b6-4ead-449e-a8f4-d0f6eb266512.jpg)

The most important part of the page is this: the Assignment Tracker. This database is used to keep track of all my assignments, from hand-out to completion.

Each assignment can take on one of six statuses: _Not Started_, _Working on It_, _Nearly Finished_, _Done &amp; Not Submitted_, _Done &amp; Submitted_, and finally, _Done_. While these labels may seem too plentiful, they have all arisen out of natural use. I have found that I need to be able to track the progress of an assignment, and I need to be able to see at a glance which assignments are done, and which are not. The _Done_ status is split into three, as I routinely had assignments that were completed but were unable to be submitted due to Moodle being down, or there being an issue with the upload process. Assignments are only ever moved to the final _Done_ if they have received feedback and a grade; I never have to think about them again.

As is visible in the View title, this Kanban board only shows incomplete assignments and those from the previous thirty days. I have a range of other view options, from large tables of all my assignments to views filtering by year.

## Investigating an Assignment
### Metadata
![A screenshot of a page. It has several properties, detailed below.](https://user-images.githubusercontent.com/14424577/230742285-a4dfead9-a39a-45cb-ac7d-4519cf53f52f.jpg)

An assignment in the database has many properties. The most interesting of which is the "Unit" property. This is a relation to a separate database, which contains all the units covered in my course, which will be discussed in the next section.

The rest of the properties are more mundane, _Grade_ and _Feedback_ are filled out once the assignment has been returned. _Due Date_ and _Handout Date_ serve to show when the assignment is expected, with _Days To/From_ being a formula based on these. _For Tutor_ is automatically populated based on the selected unit.

### Tasks

![A screenshot of a page](https://user-images.githubusercontent.com/14424577/230742293-b6553263-0612-4a9f-b7be-f2312eeb3caa.jpg)
The main body of an assignment in this system is a list of tasks. To create this, I interpret the assignment brief and pick out key tasks and information. This way, I can keep track of what is required of me, and I can see at a glance what I have done and what I have not. I find it much easier to work from this simple self-made list rather than the assignment brief itself, which is often filled with lots of unnecessary information and is not written in a way that is intuitive to me.

Each task has a large, coloured callout underneath containing the criterion that the task is being marked against. This allows me to keep tasks focused and to know exactly what is expected of me in relation to this task. If I were creating this system again, I would create a third database to contain the criteria, and then link to that from the tasks here. In practice, however, I have not found this to be a problem, since criteria is not reused and is tied to specific tasks, so this would only serve as an extra level of organisation.

## Units
![A screenshot of a table](https://user-images.githubusercontent.com/14424577/230742307-f696ec95-53cd-4f82-94c9-50f2e8553943.jpg)

The final significant database in the system is the Unit database. This contains all the units I have studied and is used to populate the "Unit" property on the Assignment database. The tutor property here is used to populate the "For Tutor" property on the Assignment database.

Unit statuses are less granular than assignments, with only _Not Started_, _Working_ and _Done_ as options. _Ass Done_ and _Ass Count_ are the count of assignments done and total, respectively. _Grade_ is the final grade for the unit.

## Notes
Eagle-eyed readers may have noticed a column in the Units table called "Notes". This relates to yet another database which I used to keep track of notes I had taken during class. This database is not shown here, but it is extremely simple; I used it as a quick scratchpad. Since creating this, I have moved my [notetaking](https://github.com/tomatsolihull/notes) to a separate application: [Obsidian](https://obsidian.md). I have found it to be a much better solution for simple notetaking, and I do not find it a hassle to make use of both Notion and Obsidian; each excel at different things.

## Conclusion
To conclude, I would like to emphasise the importance of organisation in general. I have found it exceptionally beneficial, both in my personal, professional and academic life, to be able to keep track of everything I have to do. My solution is not perfect, but it has been instrumental in achieving the grades that I have. Notion is a fantastic tool for crafting a system like this, however I implore you to find a solution that works for you. Hopefully, this short write-up has been interesting and useful to you, and I wish you the best of luck in your endeavours.
