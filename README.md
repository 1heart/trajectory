# trajectory

TDD your life.

---

Start at a single page, quick intro and login with Google.

Main page: look at the different time-length tests you have. Click into them to run them (only at the right times). You can modify/add each of them (update the questions, the times).

Inside the test, you have a list of questions to answer/modify. You can nest them in a tree.

You can also look at historical data: basically a calendar with colors for each test. You can click into each test to see the results.

---

Models:

A user.

A testtemplate. Has testblocks. Has parent user.

A testblock. Has testtemplate. Has children testblocks. Has different types of answers.

A testrun. Has snapshot of testblocks mapping to answers.

An answer. Contains the data.

---

## TODO

1. Create models and associated logic.
2. Figure out logins (Google account).
3. Build frontend
	- Landing page
	- Main page
	- Test page
4. Build historical data visualization.
5. Build email reminders.