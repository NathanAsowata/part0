```mermaid

flowchart TD
step1[The user fills the form and submits it] --> step2[The form is validated in the browser] --> step3[The note is added to the database] --> step4[The list of notes is n=updated to include the new note]


flowchart TD
step1[The browser sends a GET requets to the server] --> step2[A single HTMl page is returned with enough Javascript to populate the HTML page with necessary information]



flowchart TD

step1[User fills the form an submits] --> step2[The form is validated on the browser] --> step3[The new note is added to the existing notes]
