# Chatterwheel

A fast-talking describe-the-word party game. Play with everyone on their own phone (2–6 players, each for themselves), or in teams on one shared phone.

**Play:** open `index.html` in any browser. No install or server needed. To host it online, turn on GitHub Pages for this repo (Settings → Pages → deploy from branch, root folder).

## Playing on separate phones
This needs the published claude.ai version of the page, which provides the live room that links the phones. Every player must be signed in to Claude and have the page shared with them. One person taps **Host a game**, and the others see it in the list and tap **Join**. On your turn your phone shows the words. Tap the name of whoever guessed each one: you and that guesser both move one space.

The local `index.html` file has no room, so opened on its own it only offers one-phone mode.

## How to play (one shared phone)
1. Each turn, one person on the team is the describer; the rest of the team guesses.
2. Words come from the category of the space your team stands on: Things, Nature, Actions, Places, People or Wildcard.
3. Describe without saying the word or any part of it. Tap **Got it** or **Pass**.
4. When the timer ends, check the list and move one space per correct word.
5. First team all the way round the wheel wins.

Options: 30/45/60 second turns and a 24/36/48 space board. The game saves itself in the browser, so a refresh doesn't lose your place.
