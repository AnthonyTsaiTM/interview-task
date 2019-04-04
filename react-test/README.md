`Requirement`

  This mini project is using [jsonform library|https://jsonforms.io/docs/custom-renderers]

  It comes with some code integrated a few jsonform elements.

  The example UI is in: sample.html

`Task Objective`

  Implement 'auto complete' functionality based on the jsonform element.

`How it should work?`

  Under the 'Underlyings' section: there is a field called Underlying:isin, right now it is a free text field.

  The goal is to make the Underlying:isin field available for auto complete.

  The 'auto complete' functionality should rely on the API response (based on what user types in).

  For example: type 'LU03', the auto complete dropdown list should show top 10 suggested texts.

  e.g. LU0352132871, LU0312345677, etc

  The auto complete content should be from an external api.

  But for testing purpose, this API can be mocked by your own. It just returns some dummy data.



`Deliverables:``

  Please fork from this repository and commit to your own repository.
