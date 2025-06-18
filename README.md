# WordlePlus
A customizable Wordle-style iOS app with themes, letter count, guess limits, and alien mode.
# Project 2 - *WordlePlus*

Submitted by: **Justice Walcott**

**WordlePlus** is an app that allows users to play a customizable version of Wordle. Players can adjust the number of letters, guesses, and themes, and also enable an “alien wordle” mode where the word changes after each guess. 

Time spent: **2** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] User can change the number of letters per row (the length of the goal word)
- [x] User can change the numbers of rows on the board (how many guesses allowed)
- [x] User can select a new themed set to pull the goal word from
- [x] User can select "alien wordle", causing the goal word to change after each guess


The following **optional** features are implemented:

- [x] App displays a reset button on the top left to reset the game (but make no changes to the settings)

The following **additional** features are implemented:

- [x] The game UI updates dynamically based on settings
- [x] Goal word resets correctly when alien mode is active

## Video Walkthrough
<div>
    <a href="https://www.loom.com/share/66bbf29427fb47328ad258cd15a5a8d0">
      <p>Videos | Library | Loom - 17 June 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/66bbf29427fb47328ad258cd15a5a8d0">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/66bbf29427fb47328ad258cd15a5a8d0-85f4a933a0efc789-full-play.gif">
    </a>
  </div>

## Notes

Describe any challenges encountered while building the app.

- Making the reset button reset the board without changing settings took some careful state handling.
- Passing settings data between view controllers required using a delegate pattern properly.

## License

```text
Copyright 2025 Justice Walcott

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
