# Real-life subgrid

This simple codebase shows why subgrid is useful.

Imagine that your brief is to create a set of four content cards, each with a header, description and footer. The content in each of the cards has to align vertically across viewports and the size of the content should not break this vertical alignment - all the cards should grow and shrink to match each other.

## The examples

There are four examples in this codebase:

- `1-set-height` shows how you would create a set of content cards using "magic numbers" that quickly break as soon as the content gets too long - you don't ever want to use this kind of brittle implementation on a production site
- `2-flex-box` shows how you would create the same set of content cards using flexbox, but this is still not ideal
- `3-grid` using grid to create the content cards is a lot easier and this feels like we're on the right track
- `4-subgrid` aligning the content in the cards is suddenly a lot easier! Subgrid is intended to solve exactly this sort of problem.

## Running the examples

I just run these examples using the [LiveServer extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code. Once it's been installed you can just right-click on the `index.html` for each example and hit "Open with LiveServer"

Remember to use a browser that supports subgrid when opening the subgrid example!
