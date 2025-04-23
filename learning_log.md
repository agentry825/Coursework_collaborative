# Learning Log – Grey College JCR Website Project

## Entry 1 – Week 1: Getting Set Up and Figuring Things Out

### ✅ What I’ve Done
- Met with the JCR President to chat about what needed doing on the site and to get a rough plan.
- Took a look at how the website’s running on WSL Ubuntu and figured out how uploads were being handled via SFTP.
- Got my development environment working locally so I could test changes before pushing them live.
- Went through the new MCR content they wanted on the site and made a task list.

### 📚 What I’ve Learned
- Using `lftp` with SFTP on WSL is actually pretty straightforward, but takes some practice to avoid mistakes.
- The Linux setup meant I had to think a bit differently about file paths and permissions.
- Talking with someone non-technical (like the JCR President) helped me understand how to ask better questions.
- Planning properly at the start makes a big difference later on.

### 🎯 Goals
- Learn React properly so I can build better and more flexible site features.
- Automate uploads so I’m not doing the same repetitive stuff every time.
- Work closely with the President to make sure what I build is actually useful.
- Establish better git procedures to ensure commit messages are relevant.

### 🔜 Next Steps
- Write a Bash script to handle image uploads quickly and safely.
- Make a few small edits to the site and get feedback to build confidence.
- Start going through React tutorials to understand how components work.
- Set up a proper commit system to track what I’m doing.

---


## 📅 Entry 2 – Week 2: Small Wins and Feedback Loops

### ✅ What I’ve Done
- Wrote a Bash script to upload files using `lftp`, which now saves loads of time.
- Made small text changes and showed them to the President for feedback.
- Started building the MCR page in React with placeholder content to get the layout right.
- Committed everything to Git and showed the President the repo so he stays in the loop.
- I hosted the first meeting of the website committee!
- Some of the second and third year Comp Sci's reviewed my React component structure, and it helped me spot two bugs I missed.
- Adjusted colour choices based on feedback from a few students who found it hard to read.

### 📚 What I’ve Learned
- Automating even simple tasks improves focus—it made testing much quicker.
- Getting early feedback saved me from overbuilding something based on assumptions.
- React felt confusing at first, especially props and JSX, but breaking it into small components helped.
- GitHub collaboration worked better once I wrote proper commit messages and clear README notes.
- I initially assumed the President would want things to look a certain way, turns out he cares more about simplicity.
- I should’ve involved him earlier in some layout decisions, which lead to me having to recode stuff. Next time, I’ll mock up first before coding.
- Realised I was overcomplicating early commits; splitting changes into smaller chunks helped track issues better.

### 🎯 Goals
- Make the MCR page more polished and mobile-friendly.
- Understand React state and start handling simple user input.
- Keep version control organised and well-documented for others.

### 🔜 Next Steps
- Complete the layout for the MCR section and test on mobile.
- Start exploring React forms and managing state with `useState`.
- Ask for another round of feedback before integrating anything new.

---


## 📅 Entry 3 – Week 4: Getting into Full Stack Territory (oooohhhh)

### ✅ What I’ve Done
- Began building the backend for the pool leaderboard using Node.js and Express.
- Designed the match data format with input from the President to make it easy to use.
- Created API routes and used Postman to test submitting and retrieving results.
- Added a React form to send match data to the backend.
- Co-designed the match input process with the JCR President to keep it intuitive.
- Asked a pool team member to try the form - his feedback fixed key UX issues.
- Created a short doc to explain the system to non-technical users.

### 📚 What I’ve Learned
- Planning the API routes before writing them saved loads of time.
- Testing user input revealed edge cases I hadn’t thought about (e.g. duplicate names, typos).
- React form state was tricky at first—I had to really understand how hooks work.
- Logging and breaking backend functions into modules helped debugging massively.
- I assumed players would input perfect data, turns out typos and odd formats are really common.
- Didn’t plan for form validation until I hit errors - now adding that early in any future form.
- Backend logic became messy until I stopped and properly structured everything.

### 🎯 Goals
- Clean up the API structure and add error messages the frontend can display.
- Link the leaderboard to real-time updates from the backend.
- Start writing documentation for how everything fits together.

### 🔜 Next Steps
- Finish backend logic and test it with real data from the committee.
- Improve the React leaderboard component to pull live data.
- Add basic validation and better user feedback in the form.

---

## 📅 Entry 4 – Week 6: Fixes, Features, and Finishing Touches

### ✅ What I’ve Done
- Cleaned up the match form with better validation and helper text.
- Got the leaderboard auto-refreshing on new match submissions.
- Added fallback messages and alerts for common errors.
- Started documenting setup, deployment, and usage for the next JCR tech officer.
- Got feedback from the JCR committee after demoing the match workflow.
- Met with the web committee again where we tested the site on mobile, working together to improve the styling

### 📚 What I’ve Learned
- Good UX isn’t just about visuals, it’s about reducing user mistakes.
- Building for future maintainers made me rethink my naming and folder structure.
- It’s much easier to add features when the code is clean from the start.
- Taking small breaks before revisiting bugs helped me see problems more clearly. I tried to juggle too many tasks at once - some bugs slipped through until I slowed down.
- Focused too much on design at one point, when stability was the real need.
- Didn’t plan my backend fallback handling early enough—caused some catch-up work later.

### 🎯 Goals
- Finalise all user-facing features and test on different devices.
- Wrap up documentation and onboarding notes.
- Prepare a walkthrough video for the executive committee.

### 🔜 Next Steps
- Share a working demo with the President for a final sign-off.
- Add screenshots to the handover documentation to help future users understand the flow.
- Clean up unused code and do a last pass of refactoring.

---