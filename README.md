# NuGet Specifications

Specs for potential new features for NuGet and the NuGet Gallery

# NuGet Feature Specification Template

This document outlines the key elements needed for creating a NuGet feature specification. The different elements and sections of the document should be thought of as a helpful tool for organizing thoughts related to a feature and not as a prescription. Comments should be added in-line using GitHub's commenting capabilities.

## Status: [Ready|Working]
* Ready - has been reviewed by the community and is believed by the author to be ready for development
* Working - indicates that the author is actively working on the specification

## Overview
The purpose of this section is to describe the high level motivations for the feature.

### Problem
Describe the problem that exists currently in absence of this feature

### Solution
Describe how this feature will address the problem

#### Goals
* List out the specific goals for the feature

#### Non-Goals
* List out things that are nice-to-have but not the core goals of the feature
* This can include things like nice side-effects; they may be serendipitous, but it's helpful to have clarity around what is an explicit vs. non-explicit goal of the feature

## User Scenarios
Captures narratives from a user's perspective on how the feature will solve the problem or problems outlined above. Each scenario should be listed under a new header

### Scenario 1
Howard wants desperately to contribute a new feature to NuGet. However, he doesn't really know where to get started organizing his thoughts into a format that he can present to the NuGet development team so that it can be implemented. As he's browsing the NuGet Web site, he discovers a really great template for creating specifications. Howard gets started immediately, using the template as an outline for organizing his thoughts and fills it in with his specific feature idea. The NuGet development community is additionally happy that a proposed feature is submitted in a well-organized and well-communicated manner.

## Requirements
Captures functional and non-functional requirements. These are generally more granular and potentially orthogonal to the user scenarios, and hence exist in their own section.
* Example: Must not refresh the Web page

## Design
Captures different aspects of the proposed feature design. This can be highly variable in nature depending on the specific feature, but can include the following:
* User interface mockups 
* API design
* HTTP data flow

## Open Questions
Captures any items where the specification author wants input before taking a position in the specification.
* Each item can be captured in a simple bulleted list