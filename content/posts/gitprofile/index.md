+++
date = '2025-03-04T16:07:43+05:30'
draft = false 
tags = ["gitprofile","technology","git","profile"]
categories = ["HowTo"]
title = 'Github Stats on your Github profile page'
+++

!["featured-image](featured-image.jpg)
Ever wondered how some GitHub profiles stand out with dynamic stats, vibrant visuals, and an interactive feel? Welcome to the art of creating a dynamic GitHub profile page! In this post, we'll dive into showcasing your coding prowess through GitHub statistics to turn your profile into a living resume of your coding journey. Let's make your GitHub profile not just a page, but an experience.

## Create a GitHub Profile README:

GitHub allows you to create a special repository named after your username (e.g., `yourusername/yourusername`).

Navigate to GitHub's homepage and start creating a new repository. Set the name of the repository to your GitHub `username`.

Ensure the repository is initialised with a `README.md` file. This file will be displayed on your profile page.

## Here is how you add Dynamic GitHub Stats:

### GitHub Readme Stats:

Use services like `github-readme-stats` by [_Anurag Hazra_](https://github.com/anuraghazra) to generate dynamic stats. You can include your GitHub contributions, stars, forks, and languages used. Here's how you can add it to your README:

_Copy the Markdown link below, replacing `yourname` with your GitHub username:_

`[![yourname's GitHub stats](https://github-readme-stats.vercel.app/api?username=yourname)](https://github.com/yourname)
`

[![Murthy's GitHub stats](https://github-readme-stats.vercel.app/api?username=ugmurthy)](https://github.com/ugmurthy)

You can customise the appearance via query parameters - [more details here](https://github.com/anuraghazra/github-readme-stats).

Here is one example - adding icons and changing the theme

_Copy the Markdown link below, replacing `yourname` with your GitHub username_

`[![yourname's GitHub stats](https://github-readme-stats.vercel.app/api?username=yourname&show_icons=true&theme=radical)](https://github.com/yourname)
`

[![Murthy's GitHub stats](https://github-readme-stats.vercel.app/api?username=ugmurthy&show_icons=true&theme=radical)](https://github.com/ugmurthy)

### Displaying Specific Stats:

Top Languages: Show the languages you most frequently use by adding:

`[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=yourname)](https://github.com/yourname)
`

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ugmurthy)](https://github.com/ugmurthy)

Streak Stats: Include your coding streak with:

_Copy the Markdown link below, replacing `yourname` with your GitHub username_

`[![GitHub Streak](https://streak-stats.demolab.com?user=yourname&border_radius=6)](https://github.com/yourname)
`

[![GitHub Streak](https://streak-stats.demolab.com?user=ugmurthy&border_radius=6)](https://github.com/ugmurthy)

## Profile Readme Generator Tools:

If you're looking for a more user-friendly way, tools like

1. [GitHub Profile README Generator](https://profile-readme-generator.com/)

2. [GitHub Stats generator](https://gh-stats-gen.vercel.app/)

3. [Omsimos GitHub StatsGenerator](https://github-stats.omsimos.com/)

can help you create a personalised README with various stats and styles. These tools provide templates and easy customisation options for your profile.

I am sure there is more you can showcase such as, list your top repos and the stats relating to them - check out [GitHub Tracker](https://githubtracker.com/dashboard) in case you are interested.

That's it devs. By integrating these elements, you can enhance your GitHub profile to better showcase your coding activity and statistics. The exact customisation and choice of services depend on what you want to highlight on your profile.
