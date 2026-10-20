# SWE Cohort Hub

A one-page dashboard for the Miva Open University September 2026 Software Engineering (Computing) cohort. It shows what is coming up so nobody misses a lecture or a deadline.

**Live site:** https://sonwa127.github.io/SWE-Cohort-Hub/

## What is on it

- Upcoming key dates with a countdown (assessment close, CBT centre choice, exams begin)
- Semester progress, with the week number updating itself every Monday
- Live classes with Join and Course page buttons (times in Lagos time)
- Exam timetable (Computing programme)
- How to choose or change your elective (GST 125 or GST 127)
- A checklist for exam day
- Links and help: LMS, student portal, timetables, support contacts, Discord and the Crashout group

## How it works

The whole site is one file, `index.html`. There is nothing to install and no login. The class, exam and link data sits inside that file, so it works on any phone or browser.

## Updating it (class rep)

1. Send the new class blocks, links or announcements to Claude.
2. Download the new `index.html` it gives you.
3. In this repo, tap **Add file**, then **Upload files**, drop the new `index.html` in and tap **Commit changes**.
4. The live site refreshes in a minute or two.

## Hosting

GitHub Pages, deployed from the `main` branch, root folder (Settings, then Pages).

## Notes

- The current week is counted forward from week 7 on 20 October 2026.
- Mid-semester and end-of-semester assessments close on 15 November 2026.
- The Notion workspace "2026 SWE Miva Cohort Ops" holds the full list of links and deadlines.
- Something wrong or missing? Tell your class rep in the cohort Discord or the Crashout group.
