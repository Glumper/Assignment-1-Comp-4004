# COMP 4004 – Assignment 1
## Responsibility Traceability Table

| Responsibility ID | Responsibility Description | Relevant Use Case Steps | Number of Tests |
|---|---|---|---:|
| RESP-01 | System book collection initialization | UC-01 preconditions | |
| RESP-02 | System user accounts initialization | UC-01 preconditions | |
| RESP-03 | User authentication and credentials validation | UC-01 steps 1–3 | |
| RESP-04 | Create a session for an authenticated user | UC-01 steps 3–4 | |
| RESP-05 | Identify the authenticated user's role | UC-01 step 5 | |
| RESP-06 | Display borrower-specific operations | UC-01 extension 5a.2 | |
| RESP-07 | Display librarian-specific operations | UC-01 extension 5b.2 | |
| RESP-08 | Notify a borrower when a held title becomes available | UC-01 extension 5a.1 | |
| RESP-09 | Retrieve the borrower's current borrowed-book count | UC-02 step 1 | |
| RESP-10 | Retrieve book titles and authors for display | UC-02 step 2 | |
| RESP-11 | Determine title availability for a specific borrower | UC-02 steps 2, 6 | |
| RESP-12 | Select an available physical copy of a title | UC-02 steps 3–6 | |
| RESP-13 | Validate the borrower's borrowing eligibility | UC-02 step 7 | |
| RESP-14 | Record a borrowing transaction | UC-02 step 8 | |
| RESP-15 | Update the borrower's account after borrowing | UC-02 step 9 | |
| RESP-16 | Offer and process a hold when borrowing is unavailable | UC-02 extension 6a | |
| RESP-17 | Prevent duplicate holds and holds on titles already borrowed | UC-02 extension 6a.1 | |
| RESP-18 | Remove a borrower from the hold queue after borrowing | UC-02 hold-system rules | |
| RESP-19 | Retrieve the books currently borrowed by a borrower | UC-03 step 1 | |
| RESP-20 | Validate that a selected book is borrowed by the current borrower | UC-03 steps 1–2 | |
| RESP-21 | Process the return of a borrowed book copy | UC-03 step 4 | |
| RESP-22 | Remove the returned book from the borrower's account | UC-03 step 4 | |
| RESP-23 | Identify the next borrower waiting for a returned title | UC-03 extension 3a | |
| RESP-24 | Make a returned title available to the first borrower in its hold queue | UC-03 extension 3a.1–3a.2 | |
| RESP-25 | Determine whether a book title already exists | UC-04 step 3 | |
| RESP-26 | Create a new title and its first physical copy | UC-04 extension 3b | |
| RESP-27 | Add a physical copy to an existing title | UC-04 steps 3–4 | |
| RESP-28 | Prevent adding a copy when the title has an active hold queue | UC-04 extension 3a | |
| RESP-29 | Validate copy-number uniqueness | UC-04 steps 1–4 | |
| RESP-30 | Retrieve all book titles and their physical copies for the librarian | UC-05 step 1 | |
| RESP-31 | Validate that a selected copy is eligible for removal | UC-05 step 3 and extension 3a | |
| RESP-32 | Remove a physical copy and delete its title if no copies remain | UC-05 step 4 and post-condition | |
| RESP-33 | Clear the authenticated user's session on logout | UC-06 steps 1–3 | |
