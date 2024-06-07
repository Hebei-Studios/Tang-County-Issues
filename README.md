<div align='center'>
    <img src="./gh-assets/background.png" alt="Background" width="369" height="216">
    <h1 id="Top">Tang County Issue Tracker</h1>
    <h3>Community issue tracker, discussions for new features and enhancements for Tang County.</h3>
    <a href="https://github.com/Hebei-Studios/Tang-County-Issues/issues"><img src="https://img.shields.io/github/issues/Hebei-Studios/Tang-County-Issues.svg" alt="Issues"></a>
    <a href="https://discord.gg/rWGqsAV798"><img src="https://dcbadge.limes.pink/api/server/https://discord.gg/rWGqsAV798?style=flat" alt="Discord Shield"/></a>
</div>

## Navigation

<nav>
    <ol>
        <li><a href="#Project">Project</a></li>
        <ol>
            <li><a href="#About">About</a></li>
            <li><a href="#Issues">Reporting Issues</a></li>
            <li><a href="#Debugging">Debugging Tools</a></li>
        </ol>
        <li><a href="#Contributing">Contributing</a></li>
        <li><a href="#Links">Links</a></li>
    </ol>
</nav>

<h2 id="Project">Project</h2>

<h3 id="About">About</h3>

<p>
This repository serves as an issue tracker specifically for our Roblox community orientated around the game "Tang County". It aims to make bug reporting and suggestions an easy process. We welcome new contributors and want you to help us build a better environment for our playerbase. We value all kinds of help, you might even get awarded for it!
</p>

<h3 id="Issues">Reporting Issues</h3>

<p>
Before doing anything, we would like you to read our short guide on how to properly give feedback and criticism. First of all, please use your common senses and make sure to follow our <a href=".github/CODE_OF_CONDUCT.md">Code Of Conduct</a>.
</p>

<p>
GitHub issues are not only used to report bugs, you can also suggest new features, enhancements and discuss any changes. To open an issue, simply go to the <a hrfer="https://github.com/Hebei-Studios/Tang-County-Issues/issues">issues tab</a>. From there you can pick a template to use. For example, if you want to report a bug inside the game, use the bug report template. If you don't see a common template to use, feel free to make a custom issue with the "other" template or a completely blank issue by selecting this option at the bottom of the template list.
</p>

<p>
When opening any type of issue, make sure you provide all needed information and reason any changes you want to make. While not enforced, it is highly recommended that you attach any media like images or video about the particular bug/suggestion. This way you help us understand you and what is wrong. Issues that have good proof material will be solved quicker and prioritized over empty issues.
</p>

<p>
When opening an issue you can also sometimes set certain labels or milestones. If you think that your issue should be under a certain label, please apply it to save us some time. There are certain "special" labels that we use. If you have any doubt, you can head to the labels list and read the description of each one. We use a "stale" bot, it will automatically clean and resolve any old issues that have no activity. This bot gets automatically disabled by applying any of the following labels to an issue/pull-request: <code>no-stale, in-progress, help-wanted, critical, security</code>. When an issue reaches 14 days of inactivity, it will be automatically labeled with the "stale" label, after 7 more days (21 in total) it will be automatically closed as resolved.
</p>

<p>
You can also check out the <a href="https://github.com/Hebei-Studios/Tang-County-Issues/projects?query=is%3Aopen">projects</a> to have a quick overview of our future plans, what has been completed already, volume of issues and much more. It's a mix between Trello and Notion, if you are familiar with those tools, you won't have any issues learning it.
</p>

<h3 id="Debugging">Debugging Tools</h3>

<p>
If you are new to reporting issues, don't worry. Here is a quick guide on where to get started. All you need to know is how to screenshot the console logs inside Roblox.
</p>

<p>
The <a href="https://create.roblox.com/docs/studio/developer-console">developer console</a> in Roblox is a special tool used to check for any warnings or errors from code that runs inside the game. When making any bug report, you must check the logs and give us any output you see in there. What to do if there is an error that is constantly being spammed and you can't see what's happening clearly? Well, if that error is not related to your issue, try to reproduce the issue again in a new server. Please, make sure you don't get confused with an irrelevant error. This can waste a lot of your and our time. To learn more about it, follow the link above straight to the official Roblox documentation. This applies to any other links included in here. What we include here are the basics, you should try it out yourself in any Roblox game to see how it works.
</p>

<p>
You think there is a memory leak or your computer's RAM is about to explode? Try out the <a href="https://create.roblox.com/docs/studio/optimization/memory-usage">memory usage</a> tab to check your client's memory. Here you can browse through a lot of different categories. A memory leak happens whenever the game wanted to do something, but then it forgot to remove the object, this way it will be kept in memory forever and can stack up until your computer crashes. What to do if a server crashes? Well, you as a normal player can't really do anything useful other than giving us a report. The maximum memory a Roblox server can reach is 6.9GB. (nice) If the whole server crashes without a reason, there may be something on the other end. If you aren't a developer you won't be able to access the server's memory tab. Nevertheless please report it.
</p>

<p>
Finally, you have access to the <a href="https://create.roblox.com/docs/studio/optimization/scriptprofiler">script profiler</a> and <a href="https://create.roblox.com/docs/studio/microprofiler">micro profiler</a>. Using these tools you can identify scripts that are lagging your game or running too much useless operations. The Roblox documentation has very good explanations of how to use them, so we won't go through it here. Even if you are a mobile player, performance is important and even if you feel the slightest lag spike you should take a look into it. When reporting performance issues, please try to dump the micro profiler logs so we can take a look at them. It only costs you a press of a button and finding the HTML file on your computer.
</p>

<p>
Without any doubt, the <a href="https://devforum.roblox.com/">Roblox Developer Forum</a> is a golden resource when it comes to learning new stuff or asking questions. If you are still confused on how to use these debugging tools, you might find an better explanation there. Please, make sure you use google and the forum before asking a question here. It might have already been answered somewhere on the internet. We want to keep this guide short for newcomers to read. That's all, thank you for reading!
</p>

<h2 id="Contributing">Contributing</h2>

<p>
There are several ways how you can potentially contribute to this project. One important way to contribute is to actually <i>report bugs/issues</i> you might identify. In addition you can also bring up <i>feature/enhancements</i> requests. Another way is to <i>help translating</i> the README to a wider range of different languages by committing to the <a href="translations">translations</a> folder.
<br>
Make sure you read the <a href=".github/CODE_OF_CONDUCT.md">Code of Conduct</a> and <a href=".github/CONTRIBUTING.md">Contributing Guide</a> first, as well as all other <a href=".github">support guides</a>.
</p>

<h2 id="Links">Links</h2>

* [Game](https://www.roblox.com/games/4618049391)
* [Discord](https://discord.gg/rWGqsAV798)
* [GitHub](https://github.com/Hebei-Studios)
* [Governance](.github/GOVERNANCE.md)
* [Code Of Conduct](.github/CODE_OF_CONDUCT.md)

*Want to get a job here? Feel free to reach out in the Discord server!*

<a href="#Top"><i><u>Back To Top ⬆️</u></i></a>