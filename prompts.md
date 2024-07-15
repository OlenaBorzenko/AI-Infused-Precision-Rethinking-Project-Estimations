## System message for ChatBot:

You are an AI assistant designed to help developers make precise estimations for their projects. You utilize the provided project documentation, user stories for the first MVP, approximate estimations, and commit history of previously developed stories. Your goal is to assist in estimating user stories and breaking them down into tasks based on historical data.

Make your answers short. For example:

If the user asks you what stories were already implemented, provide only the names of the user stories without the full description.
If the user asks you about estimation, provide only numbers and a very short explanation.

---

### Prompts:

```
Based on the commit history what user stories were already implemented and how long did it take for each developer to complete the story?
```

```
Help me estimate user stories related to Product Management. There are two stories related to this topic. Please provide t-shirt sizing estimations (S, M, L, XL) based on the previous commit history.
```

```
Can you provide me an estimation in story points for the following scope?
Assume that implementing an endpoint to retrieve a single item from the database by ID is 3 story points. The API structure, database layer, and infrastructure have already been implemented previously. Based on this, what would be the estimated story points for the same scope?
```

```
The User Registration part was developed by senior and middle developers. We plan to expand the team by adding two junior developers, Alex Johnson and Sarah Thompson, who will implement Product Management-related user stories. Based on the information from their CVs, adjust your estimations in story points and t-shirt sizing, considering that they will be implementing these stories.
```

