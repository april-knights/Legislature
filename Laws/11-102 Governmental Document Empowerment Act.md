[Bill number: 11-102]: #
[Author: Archmage Szeraax]: #
[Proposed Date: 4/17/2025]: #
[Passed Date: -]: #

# Governmental Document Empowerment Act

## Purpose
To ensure that changes to the laws of the April Knights are well maintained, to reduce the maintenance burden of tracking old changes, and to increase the ease of making needed changes in the future.

It is the intent of this act to move the April Knights towards a proper Version Control System (VCS) for all official government affairs. Moving to a VCS will also have the benefit of allowing the April Knights to tighten the scope of text within the statutes, making it faster and easier to read the legislative rules while still allowing for greater insight to be available when needed.

This act does not prevent non-official usage of other systems such as google docs for government and similarly does not apply to anything that isn't part of the official governing documents of the April Knights.

## Definitions
* Bill: A proposed change to the governing rules of the April Knights that must pass both the upper and the lower council.
* Act: A legislative document.
* Statute: Specific rules related to the operation of the April Knights as designated by acts.
* Law: Any legislation that has been voted on and passed to become binding.
* Repository (Repo): A collection of related files and folders that are stored together in a single place.
* Version Control System (VCS): A generic term to describe tools that are purpose built for tracking changes to a central repository.
* Git: The most widely used VCS implementation.
* Github: The most popular website for hosting git repositories.

## Background
If passed, this act codifies the creation of separate acts and statutes for the April Knights. Statutes are the written rules that govern the order. Statutes are enacted, amended, and repealed by acts. Acts also contain the broader conversation about the statutes. Using the order's VCS, both councils will vote on acts that may each effect changes in any number of statutes.

One driving intent with this act is to make it so that it is easy for our order to preserve the work that has been done in the past (specifically the who, what, why, and when of legislation). By separating the acts from the statutes and adding appropriate metadata to the legislation (Authors, date passed, etc.), the past is indeliby written without being a maintenance burden for the order in the future. As an example, our current structure makes it hard to tell how many people have specifically amended our constitution. Using a VCS, this become trivial as all authors of changes to the constitution are tracked right along side their contributions to the constitution.

## Legislative Procedure
Acts should generally be composed with useful headings to provide additional clarity aligned with purposes such as the following:

    * Purpose: A brief overview of the change or issue it seeks to address.
    * Definitions: Anything that may need clarified within the bill text (including usage within the statutes).
    * Background: Additional context, relevant history, or justification for the bill.
    * Statutory Changes: List the documents or sections that are intended to be changed by the bill, optionally with links.
    * Enactment: When and/or how the act is to take effect along with any automatic or other expiration clause (think "implementation").

The above is not an exhaustive list of headings that may be used within an act, but should be considered a starting template when drafting a bill. Templates for suggested documents such as Bills, policy change requests, constitutional amendments ad al will be provided and expanded to assure consistency across current and future experiences. If a template doesn’t exist, it can be requested via a discussion in the Lower Council or Consult the Council ticket.

Each article or section heading may be listed with an article or section number and the heading name or just the heading name. Acts and their corresponding statutory changes should follow the markdown standard where possible.

When a statute update doesn't have a clear act associated with its change, it may be noted what the effective date of the version is along with what act caused the change (such as in the case of [8-104 (Election Act)](/Laws/8-104%20Election%20Act.md) which edited the constitution at a later date)

The authoritative list of governing documents is to be maintained by the Arcaenum and shall be known as the official April Knights repository.

### Migration Notes
There are some minor changes made to acts, as a part of migrating to the VCS, that change their links or remove specific text from the act, in order to prevent duplicating text within the repository. Preventing unnecessary duplication makes it easier to find exactly what is desired in the statutes quickly.

The [First Herald Renaming Act](/Laws/9-102%20First%20Herald%20Renaming%20Act.md) (FHRA) calls for changes that don't make sense in a VCS to the Mutare Magia Act (MMA). FHRA calls for the MMA to be updated to version 7.1. However, in the VCS, acts don't have versions or updates; once an act is passed, it never changes. Only statutes have versions because they are the documents that get edits from acts.

## Statutory Changes
All governing documents within the April Knights are officially changed as a result of this act, so they are not being listed individually. In all documents, most numbering has been removed as it is no longer needed and only increases the maintenance burden of keeping things up to date.

As the arbiters have been removed from the order, mentions of them also are removed.

The most significant changes be reviewed from this act:

* [Legislation](/Statutes/Legislation.md) (renamed from Voting to Legislation)

## Workflow
As an example of what the workflow would look like for proposing legislation:

1. Fork/clone the repo to your own git repo.
1. Create your bill in the Acts folder.
1. Enact, amend, or replease statutes as needed in the Statutes folder.
1. Submit a pull request and announce in council as normal for the legislative process.

## Enactment
This act will take effect as soon as it passes the Upper Council and Lower Council. Future changes to further simplify or make statutes more intuitive should be expected, but there are no riders that automatically enact anything more than what is contained in this act.

---
[View full history of this item](https://github.com/Szeraax/Legislature/commits/main/Laws/11-102%20Governmental%20Document%20Empowerment%20Act.md)
