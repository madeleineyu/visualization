# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      This is an example of a bad visualization: https://public.tableau.com/app/profile/daisy.jones/viz/Flavours3/FlavoursofGBBO. While it is creative and intriguing, this figure is an example of a rare type of visualization that requires time to become acquainted with the information it presents (i.e., more cognitive load). Although the frequency of the ingredients used are represented through the area of a dot/point, the total different types of possible ingredients is not immediately clear, unless you select all of the points individually. Because it also uses the channel of area to encode the frequency(?) that the ingredient is used by contestants, it actually makes it difficult to get a sense of the comparative difference in selections of these ingredients. The figure overall is also visually cluttered, which makes the readabilty and ease of processing challenging. Some lines overlap with text and it is not clear how the ingredients are ordered around the circumference of the figure. It is also not clear what can be interacted with as the lines and points are all the same grey color.

      This is an example of a good visualization: https://public.tableau.com/app/profile/agata1619/viz/JapansMostBeautifulPrefectures_17204472802890/Japan. The visualization is clear and simple, and devoid of too much competing colors or shapes which might make processing of the information more difficult. The attributes of this figure are categorical (prefectures in Japan) and ordered (top 5 most beautiful prefectures based on the 2023 Prefectural Attractiveness Ranking). The data is presented as glowing points on a map of Japan, which spatially correspond to the approximate location of the Prefecture. Restricting the number of prefectures presented to just five reduces the cognitive load required to process the information initially accessible to the viewer, and it also presents all of the prefectures at once, visually on the image of the country of Japan, which provides us with an understanding of broad geographic distance and location of these prefectures within the context of the country. There is also an option to gain more 'details on demand'; interactively selecting a point generates a list of five features of each prefecture that is relevant in its resulting ranking.

      ```
    - How could this data visualization have been improved?  
      ```
      The bad visualization could be better improved by allowing for better ease of comparability; for example, using a pie chart for each contestant of the ingredients that they each used, or using a hierarchical bar graph that includes the top 5 ingredients used by each contestant (although this could get visually busy if there are too many bars in one figure). It would also help to provide groupings (ala Gestalt Principles) of the categorical attributes: the ingredients (e.g., alphabetical, most to least used overall, category), or the contestants (e.g., order of success in the show, gender, age, alphabetical), or even which aspects of the visualization can be interacted with. I am also not sure what the purpose of the figure is -- if the purpose is to simply query the data, and compare the different ingredients used by each contestant, that is not immediately clear and the format of the figure does not aid in the cognitive load of remembering which ingredients were used by which contestants.

      Some improvements that could be made for the good visualization would be to make the association between the glowing points and the prefecture label. This is especially warranted if you are unfamiliar with the geography of Japan. Referring back to Gestalt principles, it would be also helpful if the labels of the prefecture and the points were connected objects, perhaps through the inclusion of a line that connects the two. There are also some interactions between the channels of the position and size of each point (plus the surrounding 'glow' around the point) that makes it challenging to tell apart Kyoto and Osaka, unless you interact with the figure and click on a point. It might help to provide a visual popout (e.g., contrasting colors, outline the point within the glow) so that it is immediately obvious where the points denoting prefecture are located visually. 

      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 30/04/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
