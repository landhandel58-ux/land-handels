# TODO: Implement Seller Update List Functionality

## Approved Plan
- Add "Update List" button on dashboard when list exists.
- On click, display form pre-filled with current title and items.
- On submit, update list document with new items and updatedAt timestamp.
- Move responses submitted before the new updatedAt to "oldResponses" subcollection.
- Refresh dashboard display after update.

## Steps to Complete
- [x] Step 1: Add "Update List" button in dashboard section where list details are shown.
- [x] Step 2: Implement update form logic, pre-filled with current list data.
- [x] Step 3: On form submit, update the list document in Firestore with new title, items, and updatedAt.
- [x] Step 4: Query responses where submittedAt < new updatedAt, move them to "oldResponses" subcollection.
- [x] Step 5: Refresh the dashboard display to show updated list.
- [x] Step 6: Test the update functionality and verify responses are archived correctly.
- [x] Step 7: Add functionality for seller to view old responses from "oldResponses" subcollection.
