---
layout: post
title:      "ToyFinder CLI Gem."
date:       2018-06-12 00:47:02 -0400
permalink:  toyfinder_cli_gem
---


      
Whoosh! What a relief; my ToyFinder CLI gem is finally completed.  Creating this gem was a challenging but rewarding experiences for me. First, it exposed all the gaps I had in my learning at this stage. It’s one thing to learn the theoretical aspect of a subject matter but another when those concepts must be applied in a real-world situation. I quickly realized that truth when I was sitting with a blinking cursor asking myself "now, where do I go from here?" It felt like my accumulated knowledge of the subject matter was just having understood disjointed pieces of the puzzle, not really knowing how it fitted together. One week ago, I was feeling on top of the world, because I had completed all the labs up to this point.  Now it’s “Show me what you know, buddy” time, with no training wheels.

Well, over with the complaining!  I got the inspiration for my Toyfinder Gem when I realized that the disabled segment of our population is often forgotten in terms of their needs and aspirations, mainly the special-needs children. With that in mind, I designed my CLI gem to scrape data from a site that sells adaptive toys and gadgets for these children. Outside the context of school, most parent/caregivers have no clue as what their children need for self-regulation, entertainment, and education at home. I felt that the app would be a great fit to meet that need. 

The building process involved a lot of trial-and errors until I finally settled in on the proper vehicle. At first, I decided to create a local IDE using Git Bash and Sublime Text. I watched a lot of YouTube videos until I was able to set up the platform. Then I followed Avi’s CLI Gem Walkthrough video but couldn’t get beyond the “bundle gem toy_finder” phase because Bash just doesn’t work well with the Windows system. Another possibility was to create an environment using Virtualbox, but the process would’ve compounded my frustration at that point. So, I finally settled with embedding the code in my CLI Gem assessment project (which I learned later was the intended method anyway). 

The data itself is scraped from www.funandfunction.com, which has a main page that lists all the different items based on their specialties. Once an item is selected (clicked on), a separate page displays more information about that product. Therefore, I designed the ToyFinder gem to include a CLI that interacts with the user, a separate toy.rb file that houses the scraped data, the bin folder, gemspec, and other pertinent folders that host the mechanics of the gem. The app goes one-level deep in its quest for data and provides the user with a list of 3 different toys (based on need: agitated, sleeplessness, or sensory input) to choose from. Once made, the choice will display the price and a brief description of that product. 

Frankly, the process felt like learning accounting or a new language. However, as a person who’ve learned a foreign language before from scratch, I’m familiar with the fact that once the fundamentals are fully grasped, the rest naturally falls into place and become second-nature over time.  Currently, I am beginning to see some light at the end of the proverbial tunnel; major concepts that previously seemed daunting have started to reveal themselves as I delve more into the subject matter and how they interact with one another. I know for sure that if I stay long enough on this road, I will eventually get there -  look forward to embarking upon the next phase.



