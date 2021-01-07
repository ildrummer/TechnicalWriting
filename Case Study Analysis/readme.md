# MediMaint Case Study

This case study was designed by Mike Wolfe of [Grandjean & Braverman, Inc.](https://grandjean.net/) as his primary job applicant screening tool.  I found it to be the most engaging and interesting job application I've submitted to date.  The documents in this folder demonstrate my approach to solving a broad, open-ended problem.

# Docs

## Scenario
The *MediMaint Case Study Overview* PDF lays out the situation and deliverables in one page.  It's simple - modernize a paper-based med-tech device repair company - but incorporates a lot of depth and leaves the solution completely open-ended.  This case study asks for a four-part response: client Q&A, broad solution, technical solution pseudocode, and database schema.

## Client Q&A
The *MediMaint Q&A* PDF illustrates my condensed method of probing the problem boundaries, searching for unique conditions, and figuring out key client needs.  The answers are my own and help define the problem for my solution.

## Non-Technical Proposal
The *MediMaint Proposal* PDF is a one-page solution to the problem that would be given to the client.  It's written to be understandable by non-engineers yet describe the solution and it's major tech features.

## Technical Design
The *MediMaint Technical Design* PDF contains psuedocode for the main server application that would maintain the repair queue.  It uses a priority queue but does not specify a queue implementation.  This solution solves about 80% of the problem but relies on human analysis for the remaining 20% that would be cost-prohibitive and inflexible if fully implemented.  The last page contains notes about the solution and its limitations.

## Database Schema
The *MediMaint Database Schema* PDF describes a normalized database schema suitable for storing all the necessary data described in the scenario as well as other useful client, device, and employee attributes.
