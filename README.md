# ITEE Research Funding Advisor

An AI-powered research funding chatbot for the ITEE Faculty at the University of Oulu, built for the 6G Flagship programme.

## What it does

The chatbot helps ITEE researchers find the right funding for their career stage. It covers:

- ERC grants (Starting, Consolidator, Advanced, Plus, Synergy)
- Research Council of Finland (Academy Project, Fellowship, Professorship)
- Marie Skłodowska-Curie Actions (Postdoctoral Fellowship, Doctoral Networks, Staff Exchange, Cofund)
- Horizon Europe Pillar II collaborative projects
- EIC Pathfinder
- Joint Undertakings (Chips-JU, SNS-JU)
- Interreg Aurora and other regional instruments
- Finnish foundation funding

It also points researchers to the right contacts at the University of Oulu and draws on live web search for current deadlines and call status.

## How it works

A single HTML file hosted on GitHub Pages. The chatbot calls a Cloudflare Worker proxy, which holds the Anthropic API key securely and forwards requests to Claude. The knowledge base is drawn from a University of Oulu funding information session delivered by Marianne Hiltunen, Research Funding Specialist, ITEE.

## Live URL

[https://oulu-6g.github.io/itee-funding-advisor/](https://oulu-6g.github.io/itee-funding-advisor/)

## Maintainer

Comms, 6G Flagship, ITEE Faculty, University of Oulu  


## Notes

- The chatbot uses the Anthropic Claude API (claude-sonnet). API usage incurs a small cost per conversation.
- Always verify deadlines and eligibility directly with the relevant funding body before submitting an application.
- Knowledge base last updated: March 2026.
