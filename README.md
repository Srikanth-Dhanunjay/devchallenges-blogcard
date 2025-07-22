Minimal Blog Card - A DevChallenges.io Project
This is a solution to the Minimal Blog Card challenge on DevChallenges.io. This challenge was a great opportunity to practice fundamental HTML and CSS skills by building a responsive component from a design file.

The Challenge
The goal was to build out a blog card component and get it looking as close to the provided design as possible. The challenge required careful attention to spacing, typography, colors, and layout.

Solution URL:
https://srikanth-dhanunjay.github.io/devchallenges-blogcard/

What I Learned
This project was a fantastic exercise in mastering the CSS Box Model and dealing with common layout challenges.

Key Takeaways:
The Power of box-sizing: border-box;
A major learning point was understanding how padding affects an element's total width. Initially, adding padding to an image with width: 100% caused overflow issues. Applying box-sizing: border-box; to all elements ensures that padding is included inside an element's defined width, not added to it. This was the key to creating the card's internal spacing without breaking the layout.
Strategic Use of Padding vs. Margin
I learned to differentiate between using padding for a container's internal space and margin for the space between elements. The final solution uses padding on the main .card to create the overall layout and margin-bottom on individual elements like the title and tag to control their specific spacing.
The Negative Margin Trick for Full-Width Dividers
The most interesting challenge was creating the full-width divider line. Since the line was inside a padded container, it wouldn't stretch to the edges. The solution was to use a negative horizontal margin (margin-left: -16px; margin-right: -16px;) on the divider element to make it "break out" of the parent's padding. This is a standard, professional technique for handling such design requirements.
