# TaskSplit

> A minimal workload timer that splits your available time across your
> tasks.

**TaskSplit** is a simple, local-first productivity tool inspired by
Timebleed. Set a start time, set your deadline, enter your tasks, and
TaskSplit calculates how much time you have for each one.

## Live site

Once this repository is enabled with **GitHub Pages**, the site will be
available at:

`https://ravionry.github.io/TaskSplit/`

> If your repository uses a different name or capitalization, update the
> URL above accordingly.

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

There is no build process or dependency installation required.

## GitHub Pages

To deploy TaskSplit with GitHub Pages:

1.  Push the project to a GitHub repository.
2.  Open **Settings → Pages**.
3.  Under **Build and deployment**, select **Deploy from a branch**.
4.  Select the `main` branch and `/ (root)`.
5.  Save.
6.  GitHub will publish the site.

The repository should contain the website entry point as:

``` text
TaskSplit/
├── index.html
└── README.md
```

## Design

TaskSplit uses a deliberately brutalist interface focused on speed and
clarity.

### Palette

  Color   Hex         Use
  ------- ----------- ------------------------------
  Paper   `#EEEBE5`   Background
  Ink     `#111111`   Text, borders
  Blue    `#1C4FD8`   Primary actions
  Red     `#F4405F`   Accent / destructive actions

### Principles

-   Heavy borders
-   Flat colors
-   Large typography
-   Minimal decoration
-   No unnecessary productivity features
-   One purpose: **split your available time across your tasks**

## Privacy

TaskSplit is designed to run entirely in the browser.

There is:

-   No account system
-   No server
-   No database
-   No required external API

Your task information stays in the page and is not submitted to a
TaskSplit backend.

## Tech

TaskSplit is intentionally lightweight:

-   HTML
-   CSS
-   Vanilla JavaScript

No framework or package manager is required.

## Credits

Made by [@ravionry](https://github.com/ravionry).

## License

MIT License --- see [LICENSE](LICENSE) for details.
