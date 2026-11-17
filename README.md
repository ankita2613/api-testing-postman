# API Testing with Postman: JSONPlaceholder

Tests a public practice API, https://jsonplaceholder.typicode.com, which is used only for learning.

**Tool:** Postman (collection exported as Collection v2.1)

**How to run:**
1. Open Postman and click **Import**, then choose the `.json` file from this repository.
2. Right-click the collection and click **Run collection**.

## Checks in the collection
| Request | What is checked |
| GET /users/1 | Status is 200, `id` is 1, response time under 2000 ms |
| GET /users/9999 | Status is 404 for a user that does not exist |
| POST /posts | Status is 201, the title is echoed back, a numeric `id` is created |

