# harmony_automation


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

As I am the main person responsible for data updates for Sears, there
can be upwards of 100+ tickets/logs to process on a bi-weekly basis.
Some logs can be closed after the update process, while others need to
be re-assigned for further processing.

The update process has been streamlined to the point that updates can be
easily and quickly completed in bulk/batches. Manually closing and
re-assigning up to 100+ logs at a time proved to be a tedious hassle, so
I created some scripts to automate the process using
[Selenium](https://www.selenium.dev/).

**Update:** Added a scraper bot that extends the main bot. It goes to
each log/ticket I’m assigned to and scrapes all text comments. This
minimizes the need to manually check each log in the browser.

[Documentation](https://pyronone.github.io/harmony_automation/index.html)

In action:

![Closing logs](0.gif "segment")

![Re-assigning logs](1.gif "segment")
