## DOCUMENTATION TEAM

#### Role

The documentation team’s role is to assist with improvements to concrete5’s documentation (including [editors’ guide](https://documentation.concrete5.org/editors), [developers’ docs](https://documentation.concrete5.org/developers), [tutorials](http://documentation.concrete5.org/tutorials), <a title="The concrete5 site does not currently have a FAQ.">FAQ</a><sup name="b1">[1](#e1)</sup>, [API](http://documentation.concrete5.org/api) and [YouTube](https://www.youtube.com/channel/UCywmkk3TWHLcYyKafNDFCUA)). Responsibility for source code documentation remains with GitHub contributors, although documentation team members can recommend improvements on pull requests.

#### Responsibilities

Request copies of Portland Labs’ documentation policies, standards and processes.

Research approaches taken by other projects (eg, [WordPress](https://make.wordpress.org/docs/ "WordPress Documentation Team Page")).

Draft a standard for the overall organisation and structure of documentation.<sup name="b2">[2](#e2)</sup> Considerations include:

* What are the exact types of documentation we have?<sup name="b3">[3](#e3)</sup>

* What types of documentation should we have? Possible new types:
  * A complete (demo) site creation tutorial, walking through creating and adding page types, composer forms, express entities and forms, etc. This would contrast with existing tutorials and documentation which have a very narrow focus.<sup name="b4">[4](#e4)</sup>
  * ‘Mini project tutorials’ (as per Express introduction): ‘Something with a few minor features that shows how to go from a to z, and a few of those on different types of sites’.<sup name="b5">[5](#e5)</sup>
  * ‘recipe style tutorials’ (snippets); eg, how to make image links, get thumbnails, etc.<sup name="b6">[6](#e6)</sup>
  * Glossary (with links).<sup name="b7">[7](#e7)</sup>
  * A page that just describes how things COULD be used; eg, why one would use different page types, composer use cases vs express, etc.<sup name="b8">[8](#e8)</sup>  (Or could integrate this into other documentation types.)

* What does good documentation look like for each type?<sup name="b9">[9](#e9)</sup>

* Where is our documentation good, and where does it need work?<sup name="b10">[10](#e10)</sup>

* Create one or more "templates" for different types of  documentation; ie, outlines to make it easier to structure and facilitate writing.<sup name="b11">[11](#e11)</sup>

Think about existing ‘tutorials’ section. It’s not sufficiently searchable and greater cross-referencing between similar content in different documentation sections is needed.<sup name="b12">[12](#e12)</sup>

Maintain an official GitHub repository for code samples (basic text block, multiple item block, how to use all helpers/widgets, CRUD apps, block and theme boilerplates<sup name="b13">[13](#e13)</sup>, etc.).

Develop, publish, and maintain a concrete5 documentation style guide, to assist with the production and standardisation of concrete5 documentation pages (including [editors’ guide](https://documentation.concrete5.org/editors), [developers’ guide](https://documentation.concrete5.org/developers), [tutorials](http://documentation.concrete5.org/tutorials) and FAQ). Possible features:

* clear page structure (which may be varied as required)

* describe ‘why’, not just ‘what’<sup name="b14">[14](#e14)</sup>

* relate details back to bigger picture from time to time<sup name="b15">[15](#e15)</sup>

* ‘Where docs expand on concepts from other code (Laravel, Symfony, Zend, Doctrine etc.), there needs to be both cross reference links and a TL;DR summary in place.’<sup name="b16">[16](#e16)</sup>

* If appropriate, a run through of a working example of the feature being explained.

* Indication of what version of concrete5 the documentation applies to.<sup name="b17">[17](#e17)</sup>  Assign someone to research how to relate documentation to software versions.<sup name="b18">[18](#e18)</sup>

* Split documentation into code specific documentation and user documentation so that PRs can include documentation changes.<sup name="b19">[19](#e19)</sup>

* Documentation of backward compatibility breaks.<sup name="b20">[20](#e20)</sup>

* Deprecation: when something is deprecated, state what to use instead (and ideally why).

* Present as a checklist (like PRB evaluation).

Develop a review and approval process. Approval need not depend on a specific team.<sup name="b21">[21](#e21)</sup>

Improve integration of GitHub pull request approval process and documentation process:

* ‘…no code gets approved unless the usage of that module of code is fully documented…’<sup name="b22">[22](#e22)</sup>

* ‘any docs that are submitted along with pull requests (in markdown format) can easily be added to the documentation site’<sup name="b23">[23](#e23)</sup>

* Split documentation into code specific documentation and user documentation so that PRs can include documentation changes.<sup name="b24">[24](#e24)</sup>

Manage the documentation improvement project:

* Measure the standard of current documentation.<sup name="b25">[25](#e25)</sup>

* Decide criteria to guide decisions regarding documentation priorities.

* Set a milestone for documentation improvement before c5 v9 is released.<sup name="b26">[26](#e26)</sup>

* Measure documentation progress.<sup name="b27">[27](#e27)</sup>

Motivate people to contribute to the documentation. Considerations include:<sup name="b28">[28](#e28)</sup>

* "Good for concrete5 means good for me."

* Better documentation means easier, better, faster development which translates into money through better quality products and services along with saved time.

* Promotion, help, and documentation helps attract and retain new users, designers, and developers. This means more people contributing to GitHub and making concrete5 better.

* You get more people buying from the marketplace and making developers and Portland Labs money.

* A more popular concrete5 is an easier sell to clients.

* Getting involved is a very visible way to display skills and knowledge and a great form of marketing.

React to channel inputs as follows:

Input Channel | Processes | Outputs
------------- | --------- | -------
GitHub | Ensure that every pull request provides source code PHPDocs<sup name="b29">[29](#e29)</sup> and adequate notes about new/changed/deprecated features, backward compatibility breaking changes<sup name="b30">[30](#e30)</sup>, and changes to any properties or methods<sup name="b31">[31](#e31)</sup>. Notes are not required to be formal or polished, but should describe all properties and methods and should include usage (code) examples if necessary to understand and use the feature. Adequate PHPDoc comments could suffice in some cases.<br><br>Draft documentation based on pull request notes.<br><br>Parse draft release notes (produced by the core team) to ensure that all backward compatibility breaking changes are mentioned.<sup name="b32">[32](#e32)</sup> | Prompts contributors for additional documentation notes.<br><br>New/updated documentation pages and YouTube videos(?).<br><br>Suggestions on release notes.
Documentation page comments | Address and curate comments. All useful comments should be transferred to the documentation content itself. | New/updated documentation pages and YouTube videos(?).<br><br>Bug/enhancement messages passed to the bug/enhancement team.<br><br>Remove stale/invalid documentation page comments.<sup name="b33">[33](#e33)</sup>
Forums | Questions that indicate inadequate documentation should be picked up. Such questions may be referred to the Documentation Team by the Help Team. | New/updated documentation pages and YouTube videos(?).
Slack, Stack Overflow | As for Forums (as a bonus). | As for Forums (as a bonus).

#### Team Support Requirements

Web site:

* A tracking system for documentation status. Some public visibility of this would assure users that progress is being made, could elicit suggestions, and could garner more documentation team members.

* Notifications about new comments on documentation page conversation blocks should be sent to the documentation team and/or be automatically entered into the documentation tracking database.<sup name="b34">[34](#e34)</sup>

Core team:

* The core team should dedicate a number of hours a week to providing developer documentation (or at least notes) for material that only they understand. Notes could be converted into published pages by the documentation team. The topics addressed could be indicated by the documentation tracking database.

#### Other Documentation Improvements

These improvements may be beyond the scope of the documentation team:

* Advanced FAQ page (ideally structured under headings, suitable for a large number of questions, may require CRUD capability, may require AJAX, compatible with advanced search).

* Documentation ‘advanced’ search (allowing boolean expressions, exact phrase, etc.).<sup name="b35">[35](#e35)</sup>

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

<b name="e3">3</b>:  https://concrete5.slack.com/archives/C2Q0DT1ND/p1510341021000317 [↩](#b3)

<b name="e4">4</b>:  https://concrete5.slack.com/archives/C2Q0DT1ND/p1513522200000088 [↩](#b4)

<b name="e5">5</b>:  https://concrete5.slack.com/archives/C2Q0DT1ND/p1513522200000088 [↩](#b5)

<b name="e6">6</b>:  https://concrete5.slack.com/archives/C2Q0DT1ND/p1513522200000088 [↩](#b6)

<b name="e7">7</b>:  https://concrete5.slack.com/archives/C2Q0DT1ND/p1513522200000088 [↩](#b7)

<b name="e8">8</b>:  https://concrete5.slack.com/archives/C2Q0DT1ND/p1513522200000088 [↩](#b8)

<b name="e9">9</b>:  https://concrete5.slack.com/archives/C2Q0DT1ND/p1510341021000317 [↩](#b9)

<b name="e10">10</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1510341021000317 [↩](#b10)

<b name="e11">11</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1510343414000321 [↩](#b11)

<b name="e12">12</b>: https://concrete5.slack.com/archives/C6PM5PNN8/p1513522200000088 [↩](#b12)

<b name="e13">13</b>: https://c5labs.com/concrete5-boilerplate [↩](#b13)

<b name="e14">14</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509649539000172 [↩](#b14)

<b name="e15">15</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509649539000172 [↩](#b15)

<b name="e16">16</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509649539000172 [↩](#b16)

<b name="e17">17</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509654963000642 [↩](#b17)

<b name="e18">18</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509654857000418 [↩](#b18)

<b name="e19">19</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1510341021000317 [↩](#b19)

<b name="e20">20</b>: https://github.com/concrete5/concrete5/issues/6057 [↩](#b20)


<b name="e21">21</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509654058000442, https://concrete5.slack.com/archives/C2Q0DT1ND/p1509654140000340 [↩](#b21)

<b name="e22">22</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509641357000146, https://concrete5.slack.com/archives/C2Q0DT1ND/p1509650193000328 [↩](#b22)

<b name="e23">23</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509732251000694 [↩](#b23)

<b name="e24">24</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1510341021000317 [↩](#b24)

<b name="e25">25</b>: https://concrete5.slack.com/archives/C2N3FLUBW/p1509639632000825 [↩](#b25)

<b name="e26">26</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509641474000864 [↩](#b26)

<b name="e27">27</b>: https://concrete5.slack.com/archives/C2Q0DT1ND/p1509650224000197 [↩](#b27)

<b name="e28">28</b>: https://concrete5.slack.com/archives/D6UHFHM45/p1513068743000201 [↩](#b28)

<b name="e29">29</b>: An example of high quality PHPDoc comments: https://github.com/concrete5/concrete5/blob/develop/concrete/src/Block/Block.php [↩](#b29)

<b name="e30">30</b>: See https://github.com/concrete5/concrete5/issues/6057 [↩](#b30)

<b name="e31">31</b>: The only pull requests that do not need such documentation are bug fixes. [↩](#b31)

<b name="e32">32</b>: In general, code releases and documentation updates should be tied together. [↩](#b32)

<b name="e33">33</b>: This is because the visibility of informal comments and complaints on documentation pages makes the pages look unprofessional and abandoned. [↩](#b33)

<b name="e34">34</b>: The [‘most commented’ section of Andrew Embler’s web site](http://andrewembler.com/2015/11/introducing-concrete5-community-driven-documentation) may be a suitable basis. [↩](#b34)

<b name="e35">35</b>: This could be done by integrating a third-party search tool, although a native solution would make a stronger case for concrete5. [↩](#b35)