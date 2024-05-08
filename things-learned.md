*WHEN IN DOUBT, ALWAYS READ THE DOCUMENTATION*

### may 2024
- don't code when you're sick, you'll ruin everything :|
- how to handle tests for async functions
- generally learned how to think like a developer, specifically with UI tests
- 

### april 2024
- i learned a better way to test form validation & button functions (ie clicking submit button and handlesubmit function runs).
- reminder: when tests aren't working as they should be, take not of what props your react component takes in. should this be a UI test or should you refactor and move function to it's own file (to import into component)? if doing the latter, you can test function file and use the function's arguments in the way you would use a component's props
- reminder: an important function can be the value of a local variable (ie: let value = Function(arguments))
- mock return false LOOK THIS UP!!!!!!
- freelance clients who need no/low-code solutions: either use wix studio OR webflow. webflow would be great for clients who want a prettier/"cooler" ui
- learned that jest/react testing library needs different syntax for props vs state (this should have been obvious & makes a lot of sense as to why handleSubmit on my GAP form wasn't working!!)
- learned about devops infrastructure for personal projects vs company environments (things like staging, doing a hot fix vs adding a new feature, etc)
- learned about mock data & mock data files that can be imported into multiple test files
- learned that a good rule for test coverage is "each line of code should be included in one test at minimum (can be more tests depending on project complexity)"
- when writing tests (in jest/react testing library) for async functions, you need to specify in the test that the function is async & when to await. see GAP form validation test for syntax