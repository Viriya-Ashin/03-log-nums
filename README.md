### Log Nums Tests HTML

This HTML file sets up a testing environment for functions in `log-nums.js` using Mocha and Chai.

- **Meta Tags:** Define character encoding, viewport settings, and compatibility with IE.
- **Title:** Sets the document title to "Log Nums".
- **Styles and Scripts:**
  - **Mocha CSS:** Styles the test results output.
  - **Mocha JS:** Loads the Mocha testing framework.
  - **Chai JS:** Loads the Chai assertion library.
- **Body:**
  - **Mocha Div:** Container for displaying test results.
  - **Mocha Setup:** Configures Mocha to use the BDD interface.
  - **Script Loading:**
    - `log-nums.js`: Contains the functions to be tested.
    - `log-nums.test.js`: Contains the tests for the functions in `log-nums.js`.
  - **Mocha Run:** Executes the Mocha tests.

This setup ensures a comprehensive and functional test environment for the `log-nums` functions.

### logNums Function

This JavaScript function logs numbers from 1 to a specified number:

- **logNums(num):**
  - Takes a single argument `num`.
  - Uses a for loop to iterate from 1 to `num`.
  - Logs each number to the console.

This function provides a simple way to output a sequence of numbers to the console.

