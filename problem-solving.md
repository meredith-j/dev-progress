left to do for create profile:
- update get request so that demographics submitted by patient (primary user id) are also retrieved
    - will mean refactoring most of that get request
- check for substance use/conditions/medications/family history functionality before submitting pr
- THERE'S SOME WEIRD STUFF WITH SELECTSEARCHABLE
    - why can't i use multiselect dropdowns for new users????
    - why can't i see selected values in selectsearchable where autocomplete is on?
    - should there be a height limit or something?
- why is the value of getSex used instead of the label in create profile??


later to dos:
- update select searchable with a potential shortened name for long demographics, that's the one that should be showing in select searchable
- add textinput component everywhere