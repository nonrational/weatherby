# Weatherby

Weatherby, what's the weather like?

# Requirements

Given an array of inputs (location name, postal code), log the current time and weather for those locations.

Example: `./weather New York, 10005, Tokyo, São Paulo, Pluto`

Follow our Code guidelines: [https://github.com/invisible-tech/guidelines](https://github.com/invisible-tech/guidelines)

You should use JavaScript, TypeScript is a plus.

The code should be self-documenting, although you can use comments to convey the reason for your design decisions.

Make sure you commit your progress in a sensible way. If you're doing TDD, you should start with tests.

You'll be evaluated on:

- Code consistency and naming conventions
- Use of reactive/functional paradigm
- Code abstraction
- Error Handling
- Testing
- Git commiting

When you're done, push your code to a GitHub repo and share the link here.

If you have any questions please email keenahn@invisible.email

# Tasks
- [ ] set up a node environment
- [ ] parse CSV arguments of locations
- [ ] normalize those locations (or find an api that can tolerate any location-like string)
- [ ] given a location-like string, ask what the weather is
- [ ] for each location, print the normalized version and the current weather
- [ ] if the API returns an error (as in no normalized location can be found), print that at the end.
- [ ] npm module for s's & g's?


