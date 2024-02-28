# Cypherpunk Times review process

Writing an article for [cypherpunktimes.com](https://www.cypherpunktimes.com/) consists of four main stages:

- **Stage 1:** Discuss article concept
- **Stage 2:** Create article draft
- **Stage 3:** Review/improve the draft
- **Stage 4:** Publish and support it on social media

Each stage is explained in the higher-level [process document](process.md).


## Using GitHub for these stages

Using GitHub for review process demo - https://youtu.be/AdrjFYXWpWw

* Create a GitHub account
* Ask to join [Cypherpunktimes-articles](https://github.com/PhoenixGreen/Cypherpunktimes-articles) repository


## Creating a new GitHub file to start the review process:

* Go to the [articles directory](https://github.com/PhoenixGreen/Cypherpunktimes-articles/tree/main/articles)
* Click the `Add file` button, followed by `Create new file` from the dropdown.
* In the name area, give your file a name:
  * no spaces, use hyphen `-` instead
  * all lowercase letters
  * keep it short and concise
  * add the `.md` extension at the end
  * for example: `best-coins-of-2024.md`
* Copy / paste the [article template](https://github.com/PhoenixGreen/Cypherpunktimes-articles/blob/main/article-template.md) in the text area and fill some gaps
* Press the `Commit changes…` button
* In the popup window, add a description of the article and main points.
* At the bottom of this popup window, press the `Create a new branch for this commit and start a pull request` button
* Set a simple *name of the new branch* reflecting the topic using lowercase characters
  * for example: `best-coins-2024`
* Press the `Commit changes` button
* On the next page, press the `Create pull request` button
* You are now on the pull request page for this article. Share this page link in the writers channel to start the review process.
* Reviewers can now check your thesis statement and structure. And help with feedback, questions, and research.


## Creating your article

* To edit this document, click on the pull request link and head over to the `File changes` tab and navigate to the edit button in the three dots (`…`) menu

* Write articles in a dedicated text editor e.g. Word, Google Docs, Grammarly etc… Check for grammar and spelling and structure consistency.


## Merging the article

After the article is published and publication date is known:

* Rename the file in the draft branch (i.e. in the pull request) before merging it to `main`
  * following the example set above that would be in the branch named `best-coins-2024`
  * imagine the article was published on Feb 15th, then rename `best-coins-of-2024.md` to `20240215.best-coins-of-2024.md`
  * in other words, the file path/name pattern is `articles/YYYYMMDD.short-hint.md` where `YYYYMMDD` is a date like formatted like `20240215`
* Merge the pull request
