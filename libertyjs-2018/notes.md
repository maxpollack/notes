# War Stories of Coding Standards

- "Arguments over style are pointless. There should be a style guide and you should follow it." - Rebecca Murphey
- Use git hooks via husky to enforce that JS is linted before commit. Block commits if it doesn't pass commit hooks. We could end use of hound!

# Mastering Web Performance Beyond Milliseconds

- 1/2 of web users leave website if it does not load in 3 seconds
- No brainer optimizations:
- Compression (gzip on in web configuration)
- Optimize all images on the website
- Conditional delivery - send only required content
- Google developer video that explains ways to optimize absolute speed of website delivery.
- The holiday paradox - so much information during a period of time that your brain does not have the ability to parse it all, feels like time goes fast.
- The older you get, the faster time goes for you - the age paradox.
- Users want to feel reactions to the things they have done
- Spinners: studies say that spinners remind the user that they are waiting. Users are impatient, spinners don't show any feedback on the process taking place. Could show more information relevant to the user beyond "you have to wait now."
- Showing iOS system spinner vs. a custom loading spinner shifts the blame from the application builder to the device.
- Skeleton screen feels much faster than a loading spinner or the page not changing. User will start to process the UI they're looking at vs. wait and it will prep their mind for the data they are about to see.
- How to measure perceived performance?
- If the user is waiting in the active state, the user will not recognize how fast the time goes.
- Using a little more complex animation while loading can distract the user for as much as ten seconds.
- The more engaging the loading animations are, the shorter the time feels. 20 seconds can feel like 3 seconds or less.
- "The perception of performance is just as effective as actual performance in many cases." -- apple design guidelines
