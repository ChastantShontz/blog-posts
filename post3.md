## Blog Post 3

### February 21, 2022

The testing phase of a project is arguably just as important as the building phase, for this is where you see if all your hard work yielded the desired results.  There are many different methods of testing, each one of which is applicable in a different situation.

The two main schools of thought are test-driven development and behavior-driven development.  In test-driven development, you use something called the red-green refactor cycle, which is where you first write the code so that it fails, before writing the minimum amount of additional code to make it succeed.

The code in these tests are structured according to arrange-act-assert, also called given-when-then.  The “arrange/given” part sets up the conditions, the “act/when” part completes the action, and the “assert/then” part verifies that it was a success.

These tests can take the form of unit testing, which tests only one function at a time, integration testing, which tests more than one function, and end-to-end testing, which tests the entire system at once.  Because of their complexity, end-to-end tests are the slowest to run.  They have their uses, though, for even if several individual functions pass their respective unit tests, they might not work with each other correctly.

Another approach is property-based testing, where instead of giving specific examples for the input, you input a wide array of values at once.  You can keep this up until you find the values that make the functions fail, and then compare it to the accepted margin of error.

**Test-Driven Development:**

| Unit test | Tests a single function |
| Integration test | Tests multiple functions |
| End-to-end test | Tests the entire system |
| Property-based test | Tests with multiple values at once |

With behavior-driven development, on the other hand, instead of testing on the level of individual functions, you test the system as a whole based on a predetermined set of acceptance criteria.  These criteria are drawn up by the “three amigos,” which refers to the product representative, the developer, and the tester.

All three of these individuals have their own role to play.  The product representative brings up potential flaws in the system, the developer writes the code to fix it, and the tester ensures that this problem has indeed been fixed.  Others can contribute, like the project shareholders, but these are the main three.

While it may be easier and faster to automate tests, there are times where this is not as practical, and testing must be done manually.  The two subcategories of manual testing are functional testing, which ensures that the new changes behave as expected, and regression testing, which ensures that the working of previous functions are not broken by said changes.

Visual testing, rather than testing the functionality of a webpage, instead tests to make sure that it looks the way it is supposed to.  This is another area of testing that almost always has to be done manually.  As simple as it sounds, the most effective way is to simply rely on humans to tell you what they think.

It is possible to automate visual testing, but this is not very practical and often more trouble than it is worth.  Often, automated visual tests will compare a previous screenshot of the page that was deemed passable with a newly taken screenshot to find the new changes.  It analyzes the position and color of elements on a page to see if they meet the acceptance criteria.

Sometimes, instead of the “three amigos,” there will be multi-purpose testers called quality analysts.  They conduct exploratory testing, which is where they try to get inside the heads of the users and follow the path that they would most likely take, rather than the path that the developers expect them to follow.

Finally, there is cross-functional testing, meant to test general requirements such as accessibility and security.  An example of this are load tests, also called volume tests, which tests to see if a website will function under large amounts of user traffic.  The amount of traffic that is tested against here is relative, calculated based on what type of website it is.  Sometimes, testers will increase the traffic level until the website crashes to see if it reaches an acceptable threshold.

The big drawback to load tests is that the prototype website often runs on different software than the final product, so they are not always accurate.  To fix this, some companies run load tests on their website once they have already been completed.

**Behavior-Driven Development:**

| Functional test | Tests that new changes work |
| Regression test | Tests that old functions are not broken |
| Visual test | Tests that the webpage looks good |
| Exploratory test | Tests according to what the users would do |
| Cross-functional test | Tests general requirements |
