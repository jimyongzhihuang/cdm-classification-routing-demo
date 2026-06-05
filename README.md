# CDM Classification Routing Demo

The Cabinet-Drawer Model (CDM) is an institutional classification framework. It demonstrates how the same fact, document, transaction, record, or event can produce different legal, tax, compliance, administrative, operational, or AI-governance consequences depending on the classification drawer into which it is placed.

CDM is not limited to supply chains, logistics, blockchain, taxation, or legal analysis. These are application areas. The core model is broader: it shows how institutional systems first classify information before rules, pathways, decisions, and consequences are triggered.

## Core idea

Input record → CDM drawer → Rule route → Institutional consequence

The same input can move through different institutional routes depending on the drawer label assigned to it.

For example, the same phrase “payment received” may be classified as income, gift, loan, capital contribution, reimbursement, trust distribution, or settlement proceeds. Each drawer activates a different rule path and a different downstream consequence.

## Why classification matters

Institutions do not act on raw facts alone. They act on classified facts.

Before a rule can operate, the system must decide what kind of thing it is dealing with:

* Is this amount income, capital, gift, loan, or reimbursement?
* Is this document an invoice, customs record, compliance certificate, contract, receipt, or internal note?
* Is this person an employee, contractor, shareholder, beneficiary, student, applicant, or regulated actor?
* Is this event a sale, transfer, rollover, distribution, filing, breach, approval, or trigger?

CDM makes this classification layer visible.

## Demo files

* `classification-schema.json` — JSON structure for CDM drawer classification.
* `sample-classification-table.csv` — sample table showing input records, drawers, routes, and consequences.
* `prototype.html` — simple browser demo showing how CDM routing can be displayed.
* `LICENSE` — license placeholder for this demonstration repository.

## Sample structure

| Input record               | CDM drawer           | Route                               | Institutional consequence                 |
| -------------------------- | -------------------- | ----------------------------------- | ----------------------------------------- |
| payment received           | income               | taxable income route                | income inclusion review                   |
| payment received           | gift                 | non-income / capital transfer route | no ordinary income route                  |
| property transfer          | sale                 | disposition route                   | gain/loss review                          |
| property transfer          | rollover             | deferred tax route                  | deferral review                           |
| trust distribution         | income distribution  | beneficiary income route            | income allocation review                  |
| trust distribution         | capital distribution | capital route                       | capital distribution review               |
| customs document           | import declaration   | border compliance route             | customs review                            |
| warehouse record           | inventory movement   | logistics routing route             | warehouse flow review                     |
| student application record | eligibility file     | access review route                 | admission / access decision review        |
| AI prompt input            | unsupported claim    | pre-judgment control route          | output restriction or verification review |

## Purpose

This repository provides a small public demonstration of CDM as a classification-routing model for rule-dense systems.

It can be applied across:

* law
* taxation
* trusts and estates
* education governance
* public administration
* compliance systems
* supply chains and logistics
* financial review
* AI governance
* institutional decision systems

The purpose is to show the classification layer before institutional judgment. CDM helps make visible how drawer labels shape rule pathways, access, treatment, responsibility, and downstream consequences.
