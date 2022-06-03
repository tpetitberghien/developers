## [front/react] Github user search

## Instructions

Set a search input text where users can type in and get results straight away with auto suggestions (without ENTER keypress or button required to get results), even though we could also have a submit button to help users.

Resultats are Github users formatted as a result list. Up to you to define which date to qualify users it's relevant to display here.

### The subject

1. Query against Github Api: GET https://api.github.com/search/users?q={USER}.
2. Try to not add any dependency library on a freshly created
   [create react app](https://github.com/facebook/create-react-app).
3. Don't forget to check against modern ways to make HTTP requests on frontend side.
4. Bonus: manage edge cases (no results, github api rate limit, user filling text quickly with back and forth)

### Guidelines

- Use React.js to render the view
- Push your code to a Github repository
- Document what you've done

### Evaluation

- Quality of the code
- Scalability of the algorithm
- Usage of good practices and modern javascript
