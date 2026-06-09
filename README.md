# Playlist Chaos

Your AI assistant tried to build a smart playlist generator. The app runs, but some of the behavior is unpredictable. Your task is to explore the app, investigate the code, and use an AI assistant to debug and improve it.

This activity is your first chance to practice AI-assisted debugging on a codebase that is slightly messy, slightly mysterious, and intentionally imperfect.

You do not need to understand everything at once. Approach the app as a curious investigator, work with an AI assistant to explain what you find, and make targeted improvements.

---

## How the code is organized

### `app.py`  

The Streamlit user interface. It handles things like:

- Showing and updating the mood profile  
- Adding songs  
- Displaying playlists  
- Lucky pick  
- Stats and history

### `playlist_logic.py`  

The logic behind the app, including:

- Normalizing and classifying songs  
- Building playlists  
- Merging playlist data  
- Searching  
- Computing statistics  
- Lucky pick mechanics

You will need to look at both files to understand how the app behaves.

---

## What you will do

### 1. Explore the app  

Run the app and try things out:

- Add several songs with different titles, artists, genres, and energy levels  
- Change the mood profile  
- Use the search box  
- Try the lucky pick  
- Inspect the playlist tabs and stats  
- Look at the history  

As you explore, write down at least five things that feel confusing, inconsistent, or strange. These might be bugs, quirks, or unexpected design decisions.

### 2. Ask AI for help understanding the code  

Pick one issue from your list. Use an AI coding assistant to:

- Explain the relevant code sections  
- Walk through what the code is supposed to do  
- Suggest reasons the behavior might not match expectations  

For example:

> "Here is the function that classifies songs. The app is mislabeling some songs. Help me understand what the function is doing and where the logic might need adjustment."

Before making changes, summarize in your own words what you think is happening.

### 3. Fix at least four issues  

Make improvements based on your investigation.

For each fix:

- Identify the source of the issue  
- Decide whether to accept or adjust the AI assistant's suggestions  
- Update the code  
- Add a short comment describing the fix  

Your fixes may involve logic, calculations, search behavior, playlist grouping, lucky pick behavior, or anything else you discover.

### 4. Test your changes  

After each fix, try interacting with the app again:

- Add new songs  
- Change the profile  
- Try search and stats  
- Check whether playlists behave more consistently  

Confirm that the behavior matches your expectations.

### 5. Optional stretch goals  

If you finish early or want an extra challenge, try one of these:

- Improve search behavior  
- Add a "Recently added" view  
- Add sorting controls  
- Improve how Mixed songs are handled  
- Add new features to the history view  
- Introduce better error handling for empty playlists  
- Add a new playlist category of your own design  

---

## Tips for success

- You do not need to solve everything. Focus on exploring and learning.  
- When confused, ask an AI assistant to explain the code or summarize behavior.  
- Test the app often. Small experiments reveal useful clues.  
- Treat surprising behavior as something worth investigating.  
- Stay curious. The unpredictability is intentional and part of the experience.

When you finish, Playlist Chaos will feel more predictable, and you will have taken your first steps into AI-assisted debugging.

---

## TF Weekly Task Summary

This week's tinker focused on helping students learn how to use AI tools such as GitHub Copilot as debugging partners, not just code generators. The most important concept is that students still need to understand what the code is doing, test whether it behaves as expected, and make intentional decisions about what to change. The goal is for students to stay in control of the development process instead of assuming the AI is always correct.

One place students are most likely to struggle is knowing where to begin. When an app behaves strangely in multiple places, it can be hard to tell which file or function to inspect first. A helpful strategy is to start with the intended behavior of the app, try a few specific interactions, and pay close attention to places where the actual result does not match expectations. That mismatch gives students a concrete bug to investigate and makes the debugging process feel more manageable.

AI was especially helpful when used to explain code and clarify Python behavior. It worked well for understanding what a function was doing, what assumptions a block of code was making, or how a specific Python method behaved. This kind of support helped turn confusion into a clearer debugging plan.

A strong prompt for this kind of work is: "I expected this search to return a result, but it didn't. Here is the function I think is responsible. Can you explain what this code is doing step by step and why it might behave differently than I expected?" Prompts like this are effective because they include the code, the expected behavior, and the actual behavior.

At the same time, AI was not always reliable. Sometimes it suggested refactors that made the code less readable or bug fixes that changed more than necessary. That made it important to treat AI suggestions as ideas to evaluate rather than answers to accept automatically. If a suggestion did not clearly match the problem, it was better to slow down, ask follow-up questions, or test a smaller change first.

When guiding a student without giving away the answer, a useful approach is to ask them what they expected to happen, what actually happened, and which part feels most confusing. From there, follow-up questions can help them narrow the problem down and identify the most relevant section of code. AI can also be useful for helping students understand a line of code or generate test cases, but their own reasoning and testing are what confirm whether a fix is actually correct.

One of the biggest takeaways from this week is that AI is most helpful when students use it to deepen their understanding, not replace it. The stronger and more specific their observations and questions are, the more useful the AI becomes.
