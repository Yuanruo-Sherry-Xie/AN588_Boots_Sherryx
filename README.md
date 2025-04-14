# AN588_Boots_Sherryx

-   Hi there! 😄

-   In this repo you should see the following:

    -   Orignial code (r markdown)

    -   Original code (html)

    -   Final code based off of the original code \^ (r markdown)

    -   Final code based off of the original code \^ (html)

    -   Peer commentary from Tiffany (r markdown)

    -   Peer commentary from Tiffany (html)

-   My orignial code and final code incorporates all questions asked in the HW 5 file as well as links for modules that I looked back on for this hw

-   Each section should be the title/ header before the notes and code are shown

-   I have comments in my code sections to help my readers and myself understand what's going on or my thought process in general, let me know if they are confusing

-   In my original code is also 5 struggles I encountered while doing homework 5

Thank you for reading this!👍

## 5 Struggles I Have Encountered Doing HW 5

1.  **Too Many Inconsistent Variable Names.** One major issue I faced was the lack of consistency in naming my variables. I used similar but slightly different names like boot_ci, bootstrap_ci_upper, and Boot_CI_Upper, with varying cases and underscores. This made it really difficult to remember which variable I had already created and what exactly I called it. As a result, my code wouldn't knit multiple times due to “object not found” errors, and I had to keep scrolling back to find and match the exact variable names. This taught me the importance of sticking to consistent naming conventions.
2.  **Understanding the Extra Credit Function Requirement.** At first, I found the instructions for the extra credit function a bit confusing. I wasn’t sure how to structure a function that could flexibly take in a dataset, model string, confidence level, and number of bootstraps. After re-reading the prompt several times, I was able to break it down and design a custom function called bootstrap_lm_summary(). This function accepts a data frame and model formula as arguments, fits the linear model, performs bootstrapping, and returns a summary data frame that includes both the original model's estimates and the bootstrapped statistics (means, SEs, CIs). It ended up being one of the most useful pieces of code I wrote in this assignment.
3.  **Helping a Peer Without Giving Away the Answer.** My peer review partner didn’t complete the extra credit sections, so I tried to give her encouragement and a bit of guidance on how to get started without directly giving away the solution. It was actually very difficult to explain the logic behind the function without showing the actual code. This experience helped me realize how tricky it can be to teach or explain code to others—even if you understand it yourself—because you have to think through every step and anticipate where someone else might get confused.
4.  **Rewriting Instead of Reusing My Own Code.** The extra extra credit question was even more challenging. I initially didn’t realize that I could reuse my bootstrap_lm_summary() function from the extra credit section. Instead, I wasted time rewriting a new process for each bootstrap size from scratch. Luckily, my peer Tiffany gave me the suggestion to reuse my existing function, which made everything so much simpler and more elegant. It really clicked for me at that moment how important it is to write reusable code and avoid unnecessary repetition.
5.  **Creating a Visually Clear and Informative Graph.** For the extra extra credit, I struggled with how to make a graph that was both visually clear and informative. I wanted to show the stability of the bootstrapped estimates over increasing sample sizes while also comparing them to the original model. I wasn't sure whether to use a single plot with annotations, or two separate side-by-side plots for better comparison. In the end, I created one plot showing the bootstrapped mean slope, CI bounds, and the original slope as a dashed line. I think it worked okay, but in the future I’d like to improve my ggplot skills to make even clearer visual comparisons—perhaps using facet plots or side-by-side panels for better storytelling.
