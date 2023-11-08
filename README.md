An Obsidian demo vault to help getting started with managing tasks in your 'second brain'.

- - -

# Welcome...

…to my »hands-on tasks« vault ✨

This Vault is meant to be a hands-on jump start to manage tasks in Obsidian. The goal was *not* to build a sophisticated 4D-chess task manager with fancy queries and whatnot, but to provide a robust framework as a daily driver.

Try it out, adjust what you don't like – Obsidian and its excellent community plugins offer all possibilities to do so. In fact, the fantastic [Tasks Plugin](https://github.com/obsidian-tasks-group/obsidian-tasks) offers much more sophisticated possibilities than are shown here – check out the [User Guide](https://publish.obsidian.md/tasks/Introduction)!

In case you‘re in need for a customized vault configuration [drop me an email](mailto:ltroj@posteo.de) and maybe we can work something out.


> [!Important]
> This vault contains a lot of tasks and notes. Please make sure Obsidian has finished indexing before exploring.

---

## 🚀 Getting started

### Creating tasks

This vault uses the `Tasks syntax` which looks like this:

```
- [<status>] Description (can include #tags) 🔼 (priority) 🔁 recurs (e.g. every day) 🛫 start-date ⏳ scheduled-date 📅 due-date
```

**Example**:

```
- [/] This is a task for #Project/myProject ⏫ 🔁 every week 📅 2099-01-01
```

This 👆 is a task in progress, with high priority that recurs every week with due date in 2099 and it has tag #Project/myProject tied to it.

It renders like this in Obsidian:

![screenshot of a task](https://github.com/ltroj/hands-on-tasks-vault/blob/main/screenshots/task-render-1.png?raw=true)

Use the `Tasks: Create or edit` command to open a neat GUI which makes it easy to create and edit tasks.

Note: This vault uses a feature of the Task Plugin called "Custom Statuses" to indicate that tasks are "In progress" (`- [/]`), "Forwarded" (`- [>]`), "Cancelled" (`- [-]`) and so on. Check the [Docs](https://publish.obsidian.md/tasks/Getting+Started/Statuses/Custom+Statuses) for more details.

### Collecting tasks

The cool thing about the Tasks plugin is that tasks can be cluttered in notes throughout the vault. You can easily collect them by using simple queries like this:

````
```tasks
tags include #Project/myProject
```
````

which shows all tasks assigned to that tag:

![screenshot of a task list](https://github.com/ltroj/hands-on-tasks-vault/blob/main/screenshots/task-render-2.png?raw=true)

We won't go into further detail in this short intro so check out the [User Guide](https://publish.obsidian.md/tasks/Queries/About+Queries#About+Queries) to find everything there is to know about queries and the tasks syntax.

- - - 

## ➕ Adding context to tasks

Enhancing tasks with tags makes them easily accessible and is useful when working in different contexts.

You can make the system as complex as you like, but three tags are usually enough for me:

- 🗂️ Project, Context or Topic
	- e.g. #Project/myProject or #Context/Personal
- 👤 Person (if the task is assigned to someone else, or is closely related to another person)
	- e.g. #👤/Mendoza-Jack
- ⏳ Status (if further explanation in addition to the custom status is needed)
	- e.g. #Status/info-requested/by-mail/2024-03-03 or #Status/ready-for-release/2024/03/03

That's it!

- - - 

## 📌 So – where do I put my tasklist?

I like to jot my tasks down where they cross my mind. Usually that's in my **Daily Notes,** **Project Notes** or in a **Meeting Note**. Tasks can be spread across many notes – as long as they're in the vault you can query them.

For displaying aggregated tasks this demo vault shows three useful possibilities:

- Dedicated agenda notes (like the one you find in the bottom right sidebar)
- Queries in notes such as **Daily Notes**
- Kanban-style board views using the [Cardboard Plugin](https://github.com/roovo/obsidian-card-board#obsidian-cardboard-plugin)

> [!Warning]
> This Vault contains a very large number of Tasks for demo purposes. This can cause the Cardboard plugin to freeze the Vault. Because of this, there are filters defined in the board settings ⚙️. Remove them to see all tasks in the boards (delete a number of tasks before to avoid freezing).

That's all – happy tasking!