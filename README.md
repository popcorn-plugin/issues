# Read me first!

This repository is for **reporting wrong titles ONLY**. Please don't submit issues of other topics as they will likely be ignored. For other issues please check the [Q&A](#QA) section.

**Before creating an issue, please check the guidelines** and follow the template, as it helps automate the process and in turn shinks the waiting cycle of the next update.

## How to report a wrong title?

If you are new to Github:
1. read the Github tutorial [Creating an issue](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/creating-an-issue).

2. Upon creating an issue, follow the instructions in the template. I've also created an [example issue](https://github.com/jessuni/popcorn-issues/issues/1) and it's pinned in the issue tab.


## Q&A

**Q: Can you add ratings for Prime Video/other streaming services? Why does it take so long to roll out the new feature you promised? Are you still maintaining the extension AT ALL?**

Please understand that maintaining a project is time-consuming. This is a personal side project that I started initially to enhance the Netflix watching experience for myself. Sharing it is solely out of the thought that there might be someone else who needs it. Due to the lack of time and effort, I can only maintain it in my spare time. But that doesn't mean it is abandoned.

**Q: This movie doesn't have RottenTomatoes/Metacritic ratings.**

Popcorn does not crawl any data from these sites. Instead, it uses the database provided by other developers who crawled the data. If a show doesn't have Tomatometer or Metascore, it means the database doesn't have it.

While I'll work on including other databases that contain the missing ratings, it is possible that the show you are looking for doesn't have any rating even after updates.

**Q: The Douban rating disappears when I click on one show.**

Douban API has a rather strict request limit. Netflix recently updated its UI in September 2020, but Popcorn did not optimize its request approach accordingly. Actions as simple as clicking a show will result in exceeding the request limit, but hovering on a show will not. Exceeding the request limit means for a short period (10 min or more) you can't get any ratings from Douban, but other rating sources are not affected.

The issue will be fixed soon.

**Q: Can you write a plugin for Safari/Edge?**

Due to reasons stated above, there won't be a plugin for these browsers. Edge users can update the browser to the newest version (Chromium-based)
and install the extension directly from Chrome Web Store.

---

For other questions please contact me via [email](mailto:jessunix+popcorn@gmail.com)

Thanks for making this extension better together =D
