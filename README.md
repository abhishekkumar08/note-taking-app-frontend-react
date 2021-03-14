## Notes about the app

- The `/` route is the homepage of the app and will always point to the `AllNotes` component which displays all the notes, the `/newnote` route is pointed to the `NewNote component` which contains the view to add a new note and the `/note/:id` route is pointed to the `EditNote` component which contains the view needed to edit a note. The `id` bit is what will be used to fetch that particular note's detail from the database.
