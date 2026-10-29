## Week 5 (w/c 19.10.26) Reflection

This week we held two separate meetings of around 30 minutes, one mid-week and one towards the end of the week.

### What was discussed / covered (1)? 🗣️

- Reviewed everyone’s individual EDA and compared findings, assumptions, and areas of overlap.
- Discussed the structure of the datasets and how different files related to one another.
- I volunteered to collate everyone’s individual EDA into the 500-word group summary so that others could focus on the dashboard and remaining deliverables.
- Discussed how the existing EDA could be reused where possible when moving into R Shiny development.

### What was discussed / covered (2)? 🗣️

- Completed a group wireframing session and discussed possible dashboard layouts and visualisations.
- Agreed that separating the dashboard into different tabs would make the work easier to divide and reduce the risk of overwriting each other’s changes.
- Discussed creating reusable functions for repeated components, such as leaderboards and tables, to avoid duplicating code across pages.
- Divided the dashboard work based largely on the datasets people had already explored, including Activity, Calories, Sleep, Weight, and Heart Rate-related sections.
- Agreed that people would continue development on separate branches before bringing the work together.

### Personal Reflections 💭

This week was slightly more difficult for me because I was on annual leave and had to work on the project around that. Despite this, I felt it was one of our most productive weeks so far. I was able to continue working on my EDA in R and then take responsibility for collating everyone’s individual work into the overall 500-word EDA summary. 

As R is not one of my strongest skills, particularly when it comes to developing Shiny applications, I was happy to contribute more heavily in areas such as documentation, write-ups, and Git organisation where I feel more confident. At the same time, I still wanted to contribute to the dashboard development and use the project as an opportunity to improve my understanding of Shiny rather than avoiding the technical work altogether.

During the first meeting, I asked more about how a Shiny application is structured, particularly how the UI and server components work and how visualisations are added into the app.  This helped me understand the overall structure better and made the development work feel more approachable. To build on this, I also planned some pair programming with Eleanor so that I could work through the core structure in a more practical way.

During the wireframing session, we discussed several possible ways of structuring the dashboard before settling on a multi-tab approach. The discussion was useful because the datasets naturally overlapped across areas such as activity, calories, heart rate, and weight, but our chosen method allowed for ownership of different section but also helped avoid overwriting. As Eleanor and I had both explored activity-related datasets at different levels of granularity, we agreed to work on that area together and compare our approaches before deciding what to keep.

I was also conscious of how we were using Git as the project became more implementation-focused. I felt it was important that we moved towards a clearer branch and review process as more people began changing the codebase at the same time. This became more important as the dashboard work was divided across separate sections and reusable components.

Overall, I felt this week marked a shift from exploration into implementation. We moved from understanding the data to making clearer design decisions, dividing responsibilities, and structuring the code in a more reusable way. I also felt I found a good balance between contributing through my stronger areas, such as documentation and organisation, while still deliberately developing my confidence with R and Shiny.