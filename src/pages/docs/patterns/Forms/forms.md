---
title: "Forms WIP"
description: "Forms pattern description"
layout: "guide"
weight: 1
---

## Definition

Forms is one of the most used patterns in Lexicon. Forms capture information from the user and transmits it to the system either to store, to produce an action or both at same time. Forms in Lexicon are defined to be full width.

## Usage

### Structure

Forms can be created in one single column or two columns. If your form is divided in several sections that are stacked consider not changing the internal layout between sections, it can affect the experience of filling the whole form.

When applying columns take into account that the reading directions is left-right, and up-down, in each column. So expect your user to read first column one and then column two.

### Sections

Sections help users to fill a form by chunking the form is smaller pieces. A form section is identified with an [accordion](./panel.html). There is no limitation in the number of accordions to use.

TODO: Review: In case you need to use a subsection use header X

### Fields’ lengths

Fields must occupy the space you expect your user needs to fill it. The only requirement for fields is to adapt their width to the grid so they behave properly on window resize. Sharp shape forms do not go against Lexicon but we prefer rectangular shape form as they look more clear.
In mobile view ports field lengths should be half of the screen or full length.

### Mandatory fields

Fields can be mandatory/required to fill in a form. The way to mark a field as mandatory is:

![example of mandatory field](../../../images/textfieldMandatory.png)

### Inline validation

Forms have inline validation. All form fields that can be checked against a set of rules while filling them must show success or error state to the user.

### Actions

#### General actions

General form actions always placed at the end of the form and they are always placed in same order: Primary, Secondary (default), Negative (Link). The button size to use is large.

![default image](../../../images/lexiconDefault.png)

### Interior actions

Interior form actions should not be as notorious as general actions. Therefore they use default button size.





