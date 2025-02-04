[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)


# Developed By Mr. Dev Goyal ........ and Techiebank TEAM

# Udemy Coupon Grabber & Course Enroller: Grab FREE Coupons!

Do you want to LEARN NEW STUFF for FREE? Don't worry, with the power of
web-scraping and automation, this script will find the necessary Udemy Coupons
&amp; enroll you to PAID UDEMY COURSES, ABSOLUTELY FREE!

**NOTE: THIS PROJECT IS NOT AFFILIATED WITH UDEMY.**

**NOTE: THIS PROJECT WILL NOT WORK WITH NON ENGLISH UDEMY.**

The code scrapes course links and coupons from:
 - [tutorialbar.com](https://tutorialbar.com)
 - [discudemy.com](https://discudemy.com)
 - [coursevania.com](https://coursevania.com)
 - [app.real.discount](https://app.real.discount)
 

In case of any bugs or issues, please open an issue in github.

Also, don't forget to **Fork & Star the repository if you like it!**


## Instructions

Props to Davidd Sargent for making a super simple video tutorial. If you prefer written instructions then continue reading further, else click on the image below for a quick video tutorial:

[![GET Udemy Courses for FREE with Python | 2 Minute Tuesday](https://yt-embed.herokuapp.com/embed?v=tdLsVoraMxw)](https://www.youtube.com/watch?v=tdLsVoraMxw "GET Udemy Courses for FREE with Python | 2 Minute Tuesday")

1 . Install from PyPI `pip install udemy-enroller`

- Run the script and the cli will guide you through the settings required
- If you decide to save the settings they will be stored in your home directory: <br>
**Windows**:
    C:/Users/CurrentUserName/.udemy_enroller<br>
**Linux**:
    /home/username/.udemy_enroller
    
 **The values in settings.yaml should be in the same language as the site you are browsing on**

2 . The script can be passed arguments:
- `--help`: View full list of arguments available
- `--discudemy`: Run the discudemy scraper only
- `--coursevania`: Run the coursevania scraper only
- `--tutorialbar`: Run the tutorialbar scraper only
- `--max-pages=<NUMBER>`: Max number of pages to scrape from sites before exiting the script (default is 5)
- `--delete-settings`: Delete existing settings file
- `--debug`: Enable debug logging

3 . Run the script in terminal like so:
- `udemy_enroller`

4 . The bot starts scraping the course links from the first **All Courses** page
on [Tutorial Bar](https://www.tutorialbar.com/all-courses/page/1), [DiscUdemy](https://www.discudemy.com/all) and [Coursevania](https://coursevania.com) and starts
enrolling you to Udemy courses. After it has enrolled you to courses from the
first page, it then moves to the next site page and the cycle continues.

- Stop the script by pressing ctrl+c in terminal to stop the enrollment process (in workflow by canceling it).

---

## FAQs

### 1. Can I get a specific course for free with this script?

Unfortunately no, but let me assure you that you may be lucky enough to get a
particular course for free when the instructor posts its coupon code in order
to promote it. Also, over time you would build a library of courses by running
the script often and have all the required courses in your collection. In fact,
I made this course after completing a
[Python automation course](https://www.udemy.com/course/automate/) and selenium,
which of course I got for free! :)

### 2. How does the bot work?

The bot retrieves coupon links from Tutorial Bar, DiscUdemy and Coursevania's lists to cut the prices and
then uses REST requests to authenticate and enroll to the
courses. Think of it this way: Epic Games & other clients like Steam provide you
a handful of games each week, for free; Only in this case, we need a coupon code
to make those courses free.

### 3. How frequently should you run the script?

Daily, at least once! I've painstakingly amassed over 4000
courses in the last four years! And out of those 4000, I've only paid for 4 of
these courses.

So, a mere **0.001%** of courses are **actually paid** in my collection!
Thankfully, you can get more than what I gathered in 4 years, in a matter of
weeks! 🙌🏻

### 4. Why did I create this?

It used to be my daily habit to redeem courses and it was an extremely tedious
task that took around 15 minutes, for 10 courses. And then I suddenly got the
idea to automate it, after I found the automation course mentioned above. I bet,
it will save your precious time too! :)

### 5. The code compiles successfully, but it's taking too long to work! IS there any way to fix that?

Since we are heavily dependent on a third-party site to retrieve coupons links,
there may be issues when the site is down. Needless to mention the connectivity
issues too. If everything is working fine, you can see the courses being
retrieved in the Python console/shell, which may take a while.

### 6. Which is the best way to run the script?

It is recommended to run the script using your terminal and system python.


### 7. Which branch to commit against?

Pull request should be made on "master" branch.

### 8. What's the roadmap?

Take a look at our
[Roadmap here](https://github.com/aapatre/Automatic-Udemy-Course-Enroller-GET-PAID-UDEMY-COURSES-for-FREE/projects/1)
and help us on what you want or talk to us about your proposed changes.

---

## Support & Maintenance Notice

By using this repo/script, you agree that the authors and contributors are under no obligation to provide support for the script and can discontinue it's development, as and when necessary, without prior notice. 

---
