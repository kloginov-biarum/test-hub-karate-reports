# Test Hub API tests: Allure report

The Allure report of the latest run of the Karate API tests of Test Hub, an in-house test management platform:
**https://kloginov-biarum.github.io/test-hub-karate-reports/**

GitHub Actions of the (private) test repository publishes it to the `gh-pages` branch after every run on `main`,
with the history of earlier runs for the trend charts. The tests run against Test Hub with a synthetic data set
(project `DEMO`); sessions, tokens and passwords are masked in the request logs.

Stack: Java 17, Karate 1.5, JUnit 5, Maven, Allure 2, GitHub Actions, GitHub Pages.
