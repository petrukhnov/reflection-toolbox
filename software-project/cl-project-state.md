
# Project state checklist

This checklist could help to understand complexity and state of the software system.

Some of the items do not have any positive or negative meaning. This checklist is supposed to be modified before use. 
This could be a good way to initiate discussion about potential problems.

## Overall

 - [ ] Software architecture document exists.
 - [ ] Software architecture document placed under change control.
 - [ ] Software architecture document still accurately describes the software.
 - [ ] Each developer is notified whenever there is change in software architecture document.
 - [ ] There was at least one change in software architecture document during last 3 month.
 - [ ] Architecture addresses all project's requirements.
 - [ ] Requirements traceability matrix exists.
 - [ ] Number of connections between subsystems is less than 1.5x number of subsystems.

## 3rd party vendors

 - [ ] Software is using languages, tools, components or libraries from organizations that no longer exists.
 - [ ] Software is using languages, tools, components or libraries that no longer supported.

## External software interfaces

 - [ ] Software do communicate with external systems.
 - [ ] Every external interface is documented.
 - [ ] It is possible to find list of open and closed bugs/issues for external API in less than 5 minutes.
 - [ ] Each external system have primary point of contact.

## User interfaces

 - [ ] There is interface that allow users (people) interact with the system.
 - [ ] User interface is isolated from the rest of the system.
 - [ ] There is single person overly responsible for testing UI.

## Data storage

 - [ ] Some data is(should be) stored while system is not working.
 - [ ] Database schema is documented outside of the source code.
 - [ ] There are clear rules how non-database data is stored.
 - [ ] Security processes (including GDPR, PCI-DSS, etc) for data are documented.
 - [ ] There is plan for backups.
 - [ ] Backups were validated less than a month ago.

## Performance

 - [ ] Important algorithms are documented.
 - [ ] There are tests and tools to test performance of important algorithms.
 - [ ] Performance of important algorithms tested at least every week.
 - [ ] Process for testing memory leaks and memory allocation is well documented and followed.
 - [ ] Tests for memory leaks and memory allocation is run at least every week.
 - [ ] Software is multi-threaded.
 - [ ] There are clear guidelines how are concurrency and related issues are handled.

## Localization

 - [ ] Software is expected to work in different countries.
 - [ ] Software is expected to work in different languages.
 - [ ] Software is expected to work with different page orientation.
 - [ ] Release process include tests for every combination of country, language and page orientation.
 - [ ] Tests for every combination of country, language and page orientation were performed for last 5 releases.

## Online / offline

 - [ ] Software could work when it is connected to the internet.
 - [ ] Software could work when it is not connected to the internet.
 - [ ] Software support proxy connections.

## Legacy and workarounds

 - [ ] List of legacy components and code parts exist in documentation.

## QA and error handling

 - [ ] There are zero new errors where software crashed during last 3 months.
 - [ ] Guidelines for showing errors to user (UI) are documented.
 - [ ] Software could be build with running single script/command.
 - [ ] Last 3 daily/push builds were successful.





# References
some points are taken directly from  "Software project survival guide" McConnell.