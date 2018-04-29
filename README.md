## DOCUMENTATION TEAM

#### Role

The documentation team’s role is to assist with improvements to concrete5’s documentation (including [editors’ guide](https://documentation.concrete5.org/editors), [developers’ docs](https://documentation.concrete5.org/developers), [tutorials](http://documentation.concrete5.org/tutorials), <a title="The concrete5 site does not currently have a FAQ." name="b1">FAQ</a>, [API](http://documentation.concrete5.org/api) and [YouTube](https://www.youtube.com/channel/UCywmkk3TWHLcYyKafNDFCUA)). Responsibility for source code documentation remains with GitHub contributors, although the documentation team can recommend improvements on pull requests.

#### Responsibilities

Request copies of Portland Labs’ documentation policies, standards and processes.

Research approaches taken by other projects (eg, [WordPress](https://make.wordpress.org/docs/ "WordPress Documentation Team Page")).

Draft a standard for the overall organisation and structure of documentation.<sup name="b2">[2](#e2)</sup> Considerations include:

* What are the exact types of documentation we have?

* What types of documentation should we have? Possible new types:
  * A complete (demo) site creation tutorial, walking through creating and adding page types, composer forms, express entities and forms, etc. This would contrast with existing tutorials and documentation which have a very narrow focus.
  * ‘Mini project tutorials’ (as per Express introduction): ‘Something with a few minor features that shows how to go from a to z, and a few of those on different types of sites’.
  * ‘recipe style tutorials’ (snippets); eg, how to make image links, get thumbnails, etc.
  * Glossary (with links).
  * A page that just describes how things COULD be used; eg, why one would use different page types, composer use cases vs express, etc.  (Or could integrate this into other documentation types.)

* What does good documentation look like for each type?

* Where is our documentation good, and where does it need work?

* Create one or more "templates" for different types of  documentation; ie, outlines to make it easier to structure and facilitate writing.

Think about existing ‘tutorials’ section. It’s not sufficiently searchable and greater cross-referencing between similar content in different documentation sections is needed.

Maintain an official GitHub repository for code samples (basic text block, multiple item block, how to use all helpers/widgets, CRUD apps, block and theme boilerplates , etc.).

Develop, publish, and maintain a concrete5 documentation style guide, to assist with the production and standardisation of concrete5 documentation pages (including editors guide, developers guide, tutorials and FAQ). Possible features:

* clear page structure (which may be varied as required)

* describe ‘why’, not just ‘what’

* relate details back to bigger picture from time to time

* ‘Where docs expand on concepts from other code (Laravel, Symfony, Zend, Doctrine etc.), there needs to be both cross reference links and a TL;DR summary in place.’

* If appropriate, a run through of a working example of the feature being explained.

* Indication of what version of concrete5 the documentation applies to.  Assign someone to research how to relate documentation to software versions.

* Split documentation into code specific documentation and user documentation so that PRs can include documentation changes.

* Documentation of backward compatibility breaks.

* Deprecation: when something is deprecated, state what to use instead (and ideally why).

* Present as a checklist (like PRB evaluation).

Develop a review and approval process. Approval need not depend on a specific team.

Improve integration of GitHub pull request approval process and documentation process:

* ‘…no code gets approved unless the usage of that module of code is fully documented…’

* ‘any docs that are submitted along with pull requests (in markdown format) can easily be added to the documentation site’

* Split documentation into code specific documentation and user documentation so that PRs can include documentation changes.

Manage the documentation improvement project:

* Measure the standard of current documentation.

* Decide criteria to guide decisions regarding documentation priorities.

* Set a milestone for documentation improvement before c5 v9 is released.

* Measure documentation progress.

Motivate people to contribute to the documentation. Considerations include:

* "Good for concrete5 means good for me."

* Better documentation means easier, better, faster development which translates into money through better quality products and services along with saved time.

* Promotion, help, and documentation helps attract and retain new users, designers, and developers. This means more people contributing to GitHub and making concrete5 better.

* You get more people buying from the marketplace and making developers and Portland Labs money.

* A more popular concrete5 is an easier sell to clients.

* Getting involved is a very visible way to display skills and knowledge and a great form of marketing.

React to channel inputs as follows:

Input Channel | Processes | Outputs
------------- | --------- | -------
GitHub | Ensure that every pull request provides source code PHPDocs  and adequate notes about new/changed/deprecated features, backward compatibility breaking changes , and changes to any properties or methods . Notes are not required to be formal or polished, but should describe all properties and methods and should include usage (code) examples if necessary to understand and use the feature. Adequate PHPDoc comments could suffice in some cases.<br><br>Draft documentation based on pull request notes.<br><br>Parse draft release notes (produced by the core team) to ensure that all backward compatibility breaking changes are mentioned. | Prompts contributors for additional documentation notes.<br><br>New/updated documentation pages and YouTube videos(?).<br><br>Suggestions on release notes.
Documentation page comments | Address and curate comments. All useful comments should be transferred to the documentation content itself. | New/updated documentation pages and YouTube videos(?).<br><br>Bug/enhancement messages passed to the bug/enhancement team.<br><br>Remove stale/invalid documentation page comments.
Forums | Questions that indicate inadequate documentation should be picked up. Such questions may be referred to the Documentation Team by the Help Team. | New/updated documentation pages and YouTube videos(?).
Slack, Stack Overflow | As for Forums (as a bonus). | As for Forums (as a bonus).

#### Team Support Requirements

Web site:

* A tracking system for documentation status. Some public visibility of this would assure users that progress is being made, could elicit suggestions, and could garner more documentation team members.

* Notifications about new comments on documentation page conversation blocks should be sent to the documentation team and/or be automatically entered into the documentation tracking database.

Core team:

* The core team should dedicate a number of hours a week to providing developer documentation (or at least notes) for material that only they understand. Notes could be converted into published pages by the documentation team. The topics addressed could be indicated by the documentation tracking database.

#### Other Documentation Improvements

These improvements may be beyond the scope of the documentation team:

* Advanced FAQ page (ideally structured under headings, suitable for a large number of questions, may require CRUD capability, may require AJAX, compatible with advanced search).

* Documentation ‘advanced’ search (allowing boolean expressions, exact phrase, etc.).

* Improve API reference documentation:

  * Develop a concrete5 style guide that specifies the minimum requirements for API reference documentation (PHPDoc comments).

  * Assess existing PHPDoc comment quality (focused on missing, incomplete, or outdated comments).

  * Maintain a list (database) of comments that need work.

  * Work with core team to improve comments using GitHub pull requests.

* concrete5 database structure (schema) documentation. While developers should normally use the API to access the database, some tasks (e.g. repair and maintenance jobs) need more low level access.

#### Questions

Should the documentation team be authorised to create YouTube videos for the official concrete5 YouTube channel? Videos would be subject to approval by the core team. If so, a video style guide and best practices would be required, including things like a standardized video intro and outro, resolution, and volume level etc.

#### Endnotes

<b name="e1">1</b>: The concrete5 site does not currently have a FAQ. [↩](#b1)

<b name="e2">2</b>:  https://concrete5.slack.com/archives/C2Q0DT1ND/p1509643355000562 [↩](#b2)
