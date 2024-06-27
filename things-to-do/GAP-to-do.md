
### important next steps
- finish unit tests
- refactor tests, ensure code is clean (ie: before all...) 
- finish google autocomplete
- for form page: think about merging states into one big state
- finish db routes (GET request)

### reminder for testing
- before each (render Page)
- before each/after each (look into syntax)
- describe -- validation
- describe -- ui
- describe -- repeater
- when writing tests: how does my component know this thing exists? (props vs state vs arguments)
- this test should always pass: if it fails, something is wrong (should be ammended to something is wrong OR content may have changed).
- with jest: expect.toHaveBeenCalledWith('')
- look into sync for async jest testing, spyOn, mock implementation, mock return value (for google API when it's time)
- for jest testing & functions: jest.spyOn(form, 'formValidation').mockImplementation();
- is setting up this test worth the return? ie don't worry about testing things that involve adding new packages