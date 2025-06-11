# Capstone Project: Enhanching a community library website (Demo Project)

## Description

This is a demo project for the Capstone Project: Enhanching a community library website (Demo Project). As part of a developement team tasked with enhancing a community library website, we aim to be more engaing and informative for its visitors. It currently includes basic sections: Home, About Us, Events, and Contact Us. My team decided to add a *"Book Reviews"* section and update the *"Events"* page to feature upcoming community events.

This is to simulate the roles of two contributors: *"Morgan"* and *"Jamie"*. Morgan will focus on adding the *"Book Reviews"* section, while Jamie will update the *"Events"* page with new community events.

## Objectives

- Practice cloning a working repository wth branches in Git.
- Gain experience in staging, committing, and pushing changes from both developers.
- Create pull requests and merge them after resolving any potential conflicts between the branches on review.

# Start the Project

## Setup



### Create a new repository

- Navigatge the the GitHub website and create a new repository named *"greenwood-library-website"*.

- Initialize with README.md file

![Create a new repository](../img/1.create-new-repo.png)

![Create a new repository](../img/1.2.name-repo.png)

### Clone the repository

 Navigate to the directory where you want to clone the repository and run the following command:

```bash
$ git clone https://github.com/your-username/greenwood-library-website.git
```

## Tasks

1. In the main branch, using visual studo code editor ensure there are files for each of the web pages.
    - Home.html
    - About.html
    - Events.html
    - Contact.html

2. Add any random content into each of the files.

3. Stage, commit, and push the changes to the main branch. (This is a simulation of the team's existing codebase for the website.)

![Add random content](../img/6.initial-code-base.png)

# Morgan's Work: Adding Book Reviews

1. Create a Branch for Morgan

```bash
$ git branch add-book-reviews
```

```bash
$ git checkout add-book-reviews
```

![Create a new branch](../img/7.create-new-branch.png)

2. Switch to a new branch named add-book-reviews.

```bash
$ git checkout add-book-reviews
```

![Switch to a new branch](../img/8.switch-to-new-branch.png)

3. Add a new file named *"book-reviews.html"* to represent the Book Reviews section.

```bash
$ touch book-reviews.html
```

![Add new file](../img/9.add-new-file.png)

```bash
$ git add book-reviews.html
```

![Stage changes](../img/10.stage-changes.png)

```bash
$ git commit -m "Add book reviews section"
```

![Commit changes](../img/11.commit-changes.png)

4. Add a random text content into the file.
5. Stage, commit the changes to the add-book-reviews branch.
```bash
$ git add book-reviews.html
```

```bash
$ git commit -m "Add book reviews section"
```
6. Push the *add-book-reviews* branch to the remote repository.
```bash
$ git push origin add-book-reviews
```

![Push changes](../img/12.push-changes.png)

7. Raise a PR for Morgan's Work.

![Raise PR](../img/13.raise-pr.png)

8. Review and merge Morgan's Work into the main branch.

![Merge PR](../img/14.merge-pr.png)


# Jamie's Work: Updating Events

Repeat the same work flow for Jamie's Work on Events Page. Ensure Jamie's work is in* update-events* branch.

- Pull the latest changes from the main branch into *update-events* branch.

```bash
$ git checkout update-events
$ git pull origin main
```