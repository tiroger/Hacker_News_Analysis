Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

This [dataset](https://www.kaggle.com/hacker-news/hacker-news-posts) set is Hacker News posts from the last 12 months (up to September 26 2016).

It includes the following columns:

title: title of the post (self explanatory)

url: the url of the item being linked to

num_points: the number of upvotes the post received

num_comments: the number of comments the post received

author: the name of the account that made the post

created_at: the date and time the post was made (the time zone is Eastern Time in the US)

We're specifically interested in posts whose titles begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question. Below are some examples:

---

Ask HN: Ask HN: What TLD do you use for local development?
Ask HN: Someone uses stock trading as passive income?
Ask HN: How hard would it be to make a cheap, hackable phone?

---

Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting. Below are a couple of examples:

---

Show HN: Jumble  Essays on the go #PaulInYourPocket
Show HN: Learn Japanese Vocab via multiple choice questions
Show HN: Project-Okot: Novel, CODE-FREE data-apps in mere seconds

---

We'll compare these two types of posts to determine the following:

Do Ask HN or Show HN receive more comments on average?
Do posts created at a certain time receive more comments on average?