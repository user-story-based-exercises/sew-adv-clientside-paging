SEW | CORE | Paging on the Server and the Client

## User Story 1
*As a consumer I only want 5 entries per page, so that I have a better overview of the available songs.*

### Acceptance Criteria
- A navigation for paging through the results from the server is available.
- Not all songs are loaded at once, but only the songs for the current page.
- The navigation consists of a "first page", a "previous", a "next", and a "last page" button.
- The number of the current page and the maximum number of pages is displayed.
- The "first page" button is disabled, if the user is on the first page.
- The "last page" button is disabled, if the user is on the last page.
- Each page lists 5 songs.
