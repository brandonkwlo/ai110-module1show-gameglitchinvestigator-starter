# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
   (for example: "the hints were backwards").

  **Bug Reproduction Log**

Document at least 3 bugs you found. Add rows as needed.

| Input                              | Expected Behavior                                                                          | Actual Behavior                                                                                                                                                               | Console Output / Error                                          |
| ---------------------------------- | ------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| Switching difficulties during game | Secret number, attempts, and score should reset and reflect the new difficulty's range     | The state of the game stays. Secret number is the same. Difficulty levels behave the same.                                                                                    | No error is outputted. State is same across all difficulties    |
| Starting a new game to restart     | Current game state should be deleted such as history, cleared message, and input is fresh. | Message that start a new game pop up multiple times, history is still there, and game is frozen.                                                                              | Error message: "Game over. Start a new game to try again."      |
| Playing through 1 session of game  | Possible I will correctly answer with right guess given number of attempts                 | System guides me closer to guess but once I reach the end of range, tells me to go back. Once out of attempts, the correct guess is a number that I was not getting close to. | Error message: "Out of attempts! The secret was 17. Score: -15" |

---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
