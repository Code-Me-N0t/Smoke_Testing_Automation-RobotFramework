<h1>iGAMING SMOKE TESTING AUTOMATION</h1>
<p>This automation test script is designed to test core functionalities of a gaming web application using Robotframework. Still being develop</p>

<h2>Functions</h2>
<ul>
  <li><b>Keywords:</b> Stores all the keywords needed for the testing. Includes Global and the specific keywords file for the specific test suites</li>
  <li><b>Locators:</b> Stores all the web locators used in testing.</li>
  <li><b>Output:</b> Stores the test report.</li>
  <li><b>Settings: </b> Contains the resources needed to run the automation. This includes Library Resources for the library imports, Main Resources for centralizing all the directories and files into one file, and Setup Teardown file handling the Main Setup and Main Teardown.</li>
  <li><b>Variables:</b> Stores all the variables needed for the test such as username, password, etc.</li>
  <li><b>Testsuites:</b> Stores the Test Cases written in Gherkin Syntax.</li>
</ul>

<h2>Usage</h2>
<p>To run the script, type the command below on the computer's terminal or your code editor's terminal:</p>

```shell
robot -d output testsuites
```

<ul>
  <li>"robot" command is to recognize that the file is a robot test.</li>
  <li>"-d output" is a tag to redirect the test reports to the output folder</li>
  <li>"testsuites" is the directory of your tests. You can specify the test file if the testsuites folder has two or more tests inside.</li>
</ul>
