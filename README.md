# Mermail Crypto Opportunity Desk

Unofficial companion skill for Mermail.

It turns inbound crypto opportunities into a money-first pipeline:
find → verify → score → prepare → human approve → submit.

## Why it exists

Crypto operators receive grants, RFPs, bounties, hackathon invitations and partnership requests across email. The hard part is not collecting more links; it is deciding which opportunities have the best expected value and moving the best one toward a deliverable without letting untrusted email authorize risky actions.

## Install

Keep the folder as a portable Agent Skill, or publish it in a public GitHub repository and install it with a compatible skills client.

## Demo idea

1. Show 3 mock inbound messages: a grant, a paid integration request and an explicitly authorized bug bounty.
2. Ask the agent to rank them.
3. Show the extracted reward, deadline, probability, EV and EV/hour.
4. Ask for the best next action.
5. Demonstrate that a malicious email requesting a wallet signature is flagged and cannot authorize the action.
6. End with a drafted, unsent proposal for the highest-value legitimate opportunity.
