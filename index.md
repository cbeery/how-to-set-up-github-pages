Here's you: You want to make a web page, you don't want to mess with HTML or don't even know what the hell that is, and your budget is approximately zero dollars. Keep reading. 

You'll need;

- An internet-connected computer, tablet or phone
- A second grade education or higher 
- 5 minutes 

Here's some info you don't care about, so skip the following list if you're feeling antsy: 

- [Git](https://git-scm.com/) is "version control" software used by computer nerds everywhere.
- In Git, a collection of files is called a **repository** (or, colloquially, a **"repo"**).
- [GitHub](https://github.com) ([github.com](https://github.com)) is a service that hosts Git repositories online.
- [GitHub Pages](https://pages.github.com) is a special feature of GitHub that turns a text file into a simple web page.

This page you're looking at right now is a **file** in a **Git repository**, hosted on **GitHub**, served up via **GitHub Pages**. 

Let's get fucking started. 

1. [Sign up for a GitHub account](#signup)
2. [Create a new repository ](#create-a-new-repo)
3. [Activate GitHub Pages and choose a theme](#activate-github-pages)
4. [Add your content](#add-your-content)
5. [You're basically done](#check-out-your-page)
6. [Updating your page](#edit-your-content)
7. [Advanced topics](#advanced-topics)

<a name="signup"></a>
## Create a GitHub account

If you've done this already, [fast-forward to step 2](#create-a-new-repo).

1\. Visit [githib.com](https://github.com) and "Sign up." You'll need to pick a username, provide an email address and set your password.

![](img/01-new-account.png)

2\. Select the free plan. All your repositories will be publicly viewable (but not editable), unless you choose a paid plan.

![](img/02-choose-plan.png)

 No problem with the free/public plan because the only files you'll have will be the text and pictures you want on your web page anyway.

3\. There's a third step you can skip, and they've conveniently provided a "skip this step" link at the bottom.

![](img/03-skip-step-3.png)

4\. Lastly, check your email, and confirm your email address.

![](img/04-verify-email.png)

<a name="create-a-new-repo"></a>
## Create a new repository

You'll need to make a new repository: a "project" where you keep some files.

After you *first* sign up, you can do this with the "Start a project" button.

![](img/05-start-a-project.png)

If you want to create more projects/repositories later, you can use the green "New" buttons on your profile page or your repositories page.

![](img/06-new-repo.png)
![](img/07-new-repo-2.png)

Once you've reached the "Create a new repository" page, enter the name you want for the repository/project. The description is optional. Go with the defaults on all the other stuff. Then click "Create Repository."

![](img/08-create-repo.png)

<a name="activate-github-pages"></a>
## Activate GitHub Pages and choose a theme

Once you've created the repository, you'll be looking at the contents of your initially-empty repository. Hit the Settings tab.

![](img/09-settings.png)

Scroll down to the GitHub Pages section.

![](img/10-choose-a-theme.png)

Choose a theme/layout you like, and click Select Theme.

![](img/11-select-theme.png)

>Note: You can change your theme at any time by visiting the GitHub Pages settings and choosing a different one.

<a name="add-your-content"></a>
## Add your content

After you choose your theme, GitHub puts a file called **index.md** in your repository and takes you to the page to edit it.

![](img/12-editing-index-page.png)

They're nice enough to stick some boilerplate in there to tell you some basics about [Markdown](https://guides.github.com/features/mastering-markdown/), a simple format for writing text. Why fuck around with HTML like some nerd? Stick with this Markdown crap. [Learn it](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Know it. [Live it](https://www.youtube.com/watch?v=P8E7_u2qgjE).

Replace that boilerplate with whatever you want on your page.

![](img/13-adding-my-content.png)

To save your changes, scroll down and click the "Commit changes" button.

All your life, you've clicked "Save" buttons to save your stuff, but this is nerd territory. Here you're not just "saving" your shit, you're "committing changes" to it. As far as you're concerned: same thing.

![](img/14-commit-change-button.png)

<a name="check-out-your-page"></a>
## You're done. Check out your page.

After you've saved (no, wait..."comitted") changes, you'll be looking at your **index.md** file in read mode. If you've used Markdown, you can get a preview of what that formatting looks like.

![](img/15-looking-at-index.png)

Now you want to view the thing as your actual web page. Hit the Settings tab again, scroll down to the GitHub Pages section again, and you'll see the URL for your page. Click that son of a bitch.

![](img/16-settings-again-for-url.png)

Then you'll be looking at your page.

![](img/17-here-is-your-page.png)

**Holy crap, you're done.**

```
# FYI, your page's URL is going to be:
https://<your github username>.github.io/<your repository name>
```

<a name="edit-your-content"></a>
## Updating your page

Chances are you'll want to edit your page sometimes.

Here's how the nerds do it: They'll edit their files offline on their computer in some text-editing software that you wouldn't have the slightest idea how to use, then they'll push all their changes at once using a command-line tool that's also on your own computer but you have no idea about it.

Are you going to try that? You're not some nerd. You'll just change your page right in your browser, like any person who's comfortable making eye contact with another human would do.

![](img/18-click-pencil-to-edit.png)

1. Find your **index.md** file in your repository
2. Click the little pencil icon to edit the text
3. Make any changes you want
4. Scroll down and click your old friend, the "Commit changes" button

By the way, any time you're clicking that "Commit changes" button, there's a field above it with the placeholder text "Update." You can optionally type anything you want it there, describing the changes you just made, which could be useful later when you're looking at the history of your updates/changes.

![](img/19-commit-message.png)

<a name="advanced-topics"></a>
## Advanced topics for the desperately lonely

You've probably got some semblance of a life to lead: kids to feed, a job to pretend to do, and that handle of Jamo isn't going to drink itself.

If that's not the case, some of the following may distract you from your crippling isolation.

#### Changing the page title

The [GitHub Pages themes](https://pages.github.com/themes/) stick your repo name up there as the page title, which may not be what you want.

![](img/20-repo-name-as-title.png)

You can change this. Setting a theme automatically creates a **_config.yml** file.

![](img/21-config-yml.png)

Set a title by editing the _config.yml file an adding a line like

```
title: Whatever You Want for the Title
```

![](img/22-add-title.png)

Give it a few seconds, refresh your page, and bask in your updated title.

![](img/23-title-added.png)

#### Adding additional pages

You can add more than one page by adding more Markdown files (with the `.md` extension) to your repo.

Go to the **Code** tab in your repo and click the "Create new file" button.

![](img/24-create-new-file.png)

Give the file a name with `.md` at the end, add whatever Markdown text you want, and save ("Commit new file") it.

![](img/25-add-another-page.png)

Now use your newfound Markdown skills to link to your *new* page from your *first* page. Then feel like a goddamned genius.

![](img/26-another-page.png)

#### Viewing your change history

Go hit your repo page. There's a link your your "commits."

![](img/27-commits.png)

That'll show you a list of your changes.

![](img/28-commit-history.png)

#### Using a custom domain

This is [in progress](custom-domain).


