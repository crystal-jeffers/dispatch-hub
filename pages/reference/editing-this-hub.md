# Editing This Hub
Status: Active

You don't need to know code to update this site. Every page is a plain text file. Type it the way you'd type a Word document, and the site handles the design. Each example below shows what to type, then what it turns into.

## New to GitHub? Start here

GitHub is where the site's files live. Editing a page there is like editing a shared document: open it, change the text, and save.

### What is a .md file?

A Markdown file. It's plain text with a few symbols for formatting, like a `#` for a title or a `-` for a bullet. You can open one in any text editor, but the easiest place to edit it is right on GitHub.

### Do I need an account?

Yes. Create a free GitHub account, then ask the hub owner to add you as a collaborator. You'll get an email invite.

### How do I find a page's file name?

Look at the address bar while you're on the page. Everything after `#/` is the page's location:

```
crystal-jeffers.github.io/dispatch-hub/#/kb/job-tagging
```

That page's file is `pages/kb/job-tagging.md`. Its link name is the last part, `job-tagging`. Every page also shows its link name and file at the bottom, with a Copy button.

### How do I find a picture's file name?

Click Edit this page and look for the line that starts with `![`. The file name is inside the parentheses at the end. You can also right-click a picture, choose Open image in new tab, and read the end of the address.

### What does "commit" mean?

It means save. When you click Commit changes, keep the default option, which commits straight to the main branch.

### How long until my change shows up?

About one to two minutes. If you don't see it, refresh the page. If it still looks old, hold Shift and click refresh.

### What if I break something?

Nothing is ever lost. Every saved version of every file is kept. Open the file on GitHub and click History to see older versions. If you're not sure how to fix it, tell the hub owner which page you changed.

## How to edit a page

1. Open the page on the site and click Edit this page, under the title.
2. Sign in to GitHub if asked.
3. Make your changes. Click the Preview tab to check them.
4. Click Commit changes, then Commit changes again in the box that opens.

## Titles and badges

**Type this:**

```
# Creating Purchase Orders
Platform: ServiceTitan
Status: Active
```

**You get:** the page title, with ServiceTitan and Active badges under it. The `#` line comes first and is used once per page. The Platform and Status lines go right under it.

## Sections

Start a section with `##` and a space. These exact names get their own look:

| Type this | You get |
| --- | --- |
| `## When This Is Used` | An intro with an orange bar |
| `## Steps` | Numbered step markers on a line |
| `## Required Information` | A grid of checkmarks |
| `## Common Errors` | An amber warning card |
| `## Related Articles` | Link cards |

Any other name, like `## Response times`, becomes a plain white card. Use `###` for a smaller heading inside a section.

## Lists

**Type this:**

```
- Job Type: Quoted
- Business Unit: Norcal Bay Area - HVAC
- Upload the quote to the job
```

**You get:**

- Job Type: Quoted
- Business Unit: Norcal Bay Area - HVAC
- Upload the quote to the job

A short label followed by a colon turns bold on its own. For numbered steps, use `1.` `2.` `3.` instead of dashes.

### Breaking up a long numbered list

Put a `###` heading between groups, and start the next group at the number where the last one stopped. The site keeps counting.

```
### Right away

1. Answer hotline calls.
2. Respond to customer emails.

### Next

3. Create POs for account reps.
4. Order parts and materials.
```

[Task Prioritization](task-prioritization) uses this.

## Callout boxes

**Type this:**

```
> Tip: Press the slash key to jump to search.
> Warning: Never leave Customer PO blank.
```

**You get:**

> Tip: Press the slash key to jump to search.

> Warning: Never leave Customer PO blank.

You can also use `> Note:`, `> Important:`, and `> Example:`. Leave a blank line between two callouts.

## Email templates

A `>` line without a label becomes a template card with a Copy button.

**Type this:**

```
> Hello,
> Your service request has been received.
> Thank you for your patience.
```

**You get:**

> Hello,
> Your service request has been received.
> Thank you for your patience.

## Checklists

**Type this:**

```
- [ ] Customer PO is filled in
- [ ] All POs are received
- [ ] Notes say the job is complete
```

**You get:**

- [ ] Customer PO is filled in
- [ ] All POs are received
- [ ] Notes say the job is complete

Ticks are saved in each person's own browser. Pages with four or more boxes also get a progress bar and a Clear all button.

## Quiz questions

A `###` heading that ends in a question mark, followed by checkbox answers, becomes a quiz question. Mark the right answer with `[x]`. A `> Why:` line under the answers appears after someone picks one.

**Type this:**

```
### Which button saves your changes on GitHub?

- [ ] Preview
- [x] Commit changes
- [ ] Edit

> Why: Committing is how GitHub saves. Preview only shows you how it will look.
```

**You get:**

### Which button saves your changes on GitHub?

- [ ] Preview
- [x] Commit changes
- [ ] Edit

> Why: Committing is how GitHub saves. Preview only shows you how it will look.

## Decision trees

A line that ends in a question mark, followed by two or more `### If` headings, becomes a branching diagram. An `### In every case` heading after the branches joins them back together.

**Type this:**

```
Did the parts arrive?

### If yes

1. Tell the technician.
2. Schedule the job.

### If no

1. Check the tracking.
2. Update the customer.

### In every case

1. Update the job notes.
```

**You get:**

Did the parts arrive?

### If yes

1. Tell the technician.
2. Schedule the job.

### If no

1. Check the tracking.
2. Update the customer.

### In every case

1. Update the job notes.

[Direct Line](direct-line) uses this.

## Fillable forms

Add `Type: Form` under the title. Then any bullet that ends in three underscores becomes a box people can type in. Eight or more underscores make a bigger box. Form pages get a Print or save as PDF button, and nothing typed is saved.

```
# Service Request Intake Form
Type: Form

- Company name: ___
- Description of the issue: ________
```

See the [Intake Form](intake-form) for a full example.

## Links

To link to another page, put the words in square brackets and the page's link name in parentheses:

```
See [Job Tagging](job-tagging) for the tag list.
```

You get: See [Job Tagging](job-tagging) for the tag list.

For SharePoint, add the link to [Shared Links](shared-links) first, then use its name in lowercase with dashes. SharePoint links get a lock badge on their own:

```
The directory is in the [Onboarding Folder](onboarding-folder).
```

You get: The directory is in the [Onboarding Folder](onboarding-folder).

## Pictures

1. On GitHub, open the `assets/img` folder.
2. Click Add file, then Upload files, and drag your picture in. Name it in lowercase with dashes, like `receiving-pos-01.png`.
3. Click Commit changes.
4. In the article, add a line with the caption and file name:

```
![Click Receive, then upload the invoice](receiving-pos-01.png)
```

Put two or more picture lines back to back and they become a slideshow with arrows:

![The Supervisor Dashboard workflow](supervisor-dashboard-overview-01.png)
![The parts ordering workflow](parts-ordering-workflow-01.png)

> Warning: Before uploading a screenshot, blur names, emails, phone numbers, account numbers, customer details, and dollar amounts. This site is public.

## Archiving a page

Change its status line to `Status: Archived`. That's all. The page leaves the menu and moves to the Archive page on its own. Archive, Deprecated, Retired, and Legacy all work, in any capitals.

To bring it back, change the line to `Status: Active`.

## Adding a new page

1. On GitHub, open the right folder under `pages`, like `pages/kb`.
2. Click Add file, then Create new file.
3. Name it in lowercase with dashes, ending in `.md`, like `ordering-filters.md`.
4. Start it with `#`, a space, and the title. Then commit.
5. Ask the hub owner to add it to the menu.

## Extra space

Leave two or more blank lines between paragraphs to add extra space on the page.
