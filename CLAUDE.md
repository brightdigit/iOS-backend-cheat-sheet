# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a **documentation repository**, not a code project. It provides a comprehensive guide for iOS developers choosing backend solutions for their apps. The repository contains:

- **README.md**: The primary content file containing a decision tree, backend comparisons, and technical guidance
- **LICENSE**: Creative Commons Attribution-ShareAlike 4.0 International License

## Content Structure

The README.md is organized into these key sections:

1. **Decision Tree**: A Mermaid diagram that visualizes the backend selection process based on project requirements
2. **Backend Options Overview**: Detailed comparisons of different backend solutions (CloudKit, Firebase, AWS Lambda, PaaS, VMs)
3. **Swift on the Server Options**: Frameworks and deployment options for server-side Swift
4. **Technical Considerations**: Data complexity, database options, and load patterns
5. **Deployment & Cost Considerations**: Infrastructure and cost planning guidance
6. **About BrightDigit**: Company information and services
7. **Further Reading**: Links to related articles, podcasts, and resources

## Working with the Decision Tree

The Mermaid diagram at the top of README.md is a critical visual element. When updating:

- Ensure the diagram logic matches the content in the Backend Options sections
- Test the Mermaid syntax renders correctly (use GitHub's preview or a Mermaid live editor)
- Keep decision points clear and mutually exclusive
- Update the Note subgraph if Swift deployment options change

## Content Guidelines

When editing the README.md:

- **Maintain consistency** between the decision tree and the detailed backend descriptions
- **Keep links up to date**: Verify external links to services, documentation, and BrightDigit content still work
- **Update technical accuracy**: Backend services and pricing models change frequently
- **Preserve the structure**: The table of contents and section hierarchy help users navigate
- **Respect the license**: This is CC BY-SA 4.0, requiring attribution and share-alike terms

## Branch Context

- **main**: Production version of the guide
- **2-firebase**: Current branch, likely adding or updating Firebase-related content

## Making Changes

When adding or updating backend information:

1. Check if the decision tree logic needs updating
2. Update the relevant Backend Options Overview section
3. Verify links and technical details are current
4. Consider if Deployment or Cost Considerations sections need updates
5. Update the Further Reading section if referencing new BrightDigit articles or podcasts

## No Build Process

This repository has no build, test, or lint commands. Changes are made directly to markdown files and committed via git.
