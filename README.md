# TaskSplit

> A minimal workload timer that splits your available time across your
> tasks.

**TaskSplit** is a simple, local-first productivity tool inspired by
Timebleed. Set a start time, set your deadline, enter your tasks, and
TaskSplit calculates how much time you have for each one.

## Features

-   Set an exact **start date + time**
-   Set an exact **end date + time**
-   Add and remove tasks
-   Automatically calculate the available time
-   Automatically split the available time between tasks
-   Live countdown for each task
-   Pause and resume
-   Finish a task early and redistribute the saved time
-   Add 5 minutes to the current task
-   Respects the selected deadline
-   Responsive brutalist UI
-   No account
-   No backend
-   No database
-   Runs entirely in the browser

## How it works

For example:

**Start:** 7:00 PM\
**End:** 10:00 PM\
**Tasks:** 4

TaskSplit calculates:

**3 hours ÷ 4 tasks = 45 minutes per task**

If you finish a task early, the saved time is redistributed across the
remaining tasks.

## Getting started

### Use the website

Open the GitHub Pages site and:

1.  Choose your start date and time.
2.  Choose your end date and time.
3.  Add your tasks.
4.  Click **Initialize workload**.
5.  Start working.

### Run locally

Clone the repository:

``` bash
git clone https://github.com/ravionry/TaskSplit.git
cd TaskSplit
```

Then open `index.html` in your browser.

## License

MIT License --- see [LICENSE](LICENSE) for details.
