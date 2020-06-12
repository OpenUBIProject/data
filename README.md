# OpenUBI Data

**👋 Welcome to the OpenUBI data repository! If you do not having any experience with code or GitHub, you will still be able to contribute to the data, probably in less than 10 minutes! If you're having trouble, feel free to contact one of us for help.**

---

This repository contains the data for the [UBI Caucus candidates site](https://support.us.openubiproject.org). You can suggests edits to this data, including the addition, removal, and modification of candidates.

If you've used GitHub before and are familiar with contributing, feel free to go ahead and make a pull request. If you're not, we've compiled a guide below on how to contribute. Feel free to reach out to one of us for help or further clarification.

## How to suggest edits to the data

This guide will help you suggest edits to the data. This could be adding or removing a candidate, or adding/updating information about a candidate such as Twitter handle or donation link. Let's get started!

### 1. Sign up (or sign in) to GitHub
Simply click "sign in" or "sign up" in the top right corner! Once you're logged in, you can continue with the steps below.

### 2. Open the `candidates.yaml` file.
You will see a file above this called `candidates.yaml`. Click on that file to open it. YAML is a file format for storing data. It is readable for computers _and_ humans, which makes it a good format to use for this project.

### 3. Click on the "edit" button.
You will find this icon at the top right, just above the start of the actual file, next to the trash can icon. Click on this button to start editing the file.

### 4. Edit the file.
You should now be able to edit the text inside the file. Note that these edits will not be applied immediately, one of the admins will have to approve them first. So don't worry about stuffing things up, just do your best and we will work with you to make sure that everything is formatted correctly.

Each candidate starts with a `-`. Think of it like a list of bullet points, with each candidate getting their own bullet point. All the lines under the bullet point belong to that candidate, until the next bullet point. All the lines after the bullet point should be indented with 2 spaces.

Each candidate can have the following fields:
- `name`: This field is required. Type the candidate's name, surrounded by quotation marks (`"`).
- `runningFor`: This field is required. You can type either `house`, `senate`, or `president`. You don't need quotes.
- `state`: The two-letter code for the state that the candidate is running in. You don't need to include this field if the candidate is running for president. You don't need quotes.
- `district`: The district number that the candidate is running in. You don't need to include this field if the candidate is running for president or for senate. You don't need quotes.
- `twitterHandle`: The candidate's Twitter username, not including an `@` symbol at the start. You don't need quotes. This field is not required, but is preferred, since that's where candidate images are sourced from.
- `websiteLink`: The link to the home page of the candidate's website, surrounded by quotation marks. The link must start with `http://` or `https://`. This field is not required.
- `donationLink`: The link to the home page of the candidate's donation page, surrounded by quotation marks. The link must start with `http://` or `https://`. This field is not required.

### 5. Commit the changes
Once you're happy with your suggested edits, you can 'commit' the changes. This is similar to a "save" or "submit" button.

Scroll down to the bottom of the page, and in the field that says "Update candidates.yaml", type a short description of what you changed. For example, "Added John Smith", or "Updated donation link for David Kim".

Once you've filled that out, click the "Propose changes" button!

### 6. Click on "create pull request"
There's one more button you need to click, and then you're done! On the screen that comes up, there will be a form, and a "create pull request" button. You can simply click on that button straight away! Or you can leave a comment before clicking the button, if there's anything you want to mention or let us know about.

### 7. All done!
Your suggested edits have now been submitted, and the admins have been notified via email!

If everything looks good, we'll "merge" your pull request. This means that the file has been updated with your changes, and they should appear on the site shortly.

If your edits need improvement &mdash; this could be formatting or data related &mdash; we will either edit your changes ourselves, or post a comment discussing the changes. You will be notified of this at the email address which you signed up to GitHub with (you can unsubscribe at any time).

Okay, that's it! Thanks for your interest in helping keep this data and the site complete and up to date! As earlier, feel free to contact us if you need help.


## Other ways to contribute
If you find an issue with the documentation above, or want to improve it, feel free to create a pull request for this file, similar to the process above.
