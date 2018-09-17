# MonsterEOS - Decentralized Autonomous Organization

Our Decentralized Autonomous Organization is still being defined. This model is inspired by [Slicing Pie](https://slicingpie.com/) for startups companies, believing that it's the fairest way to reward collaborators in an open source project. We intend to translate it into an EOS Smart Contract and automate the distribution process in the future.

# Contribution Framework

We mixed the concept of regular shares from Slicing Pies with a headboard dividends. The headboard is the responsible for making decisions and also supporting the base of the project.

## Head Board Composition

The headboard, similar to EOS Blockchain, is composed of 21 seats. These seats are used to weight in dividends and voting decisions.

- Leo Ribeiro, the Founder and Head of Development, currently holds 7 (seven) seats.
- Alex Rozgo, the Head of Gaming Engineering and Arts, currently holds 6 (six) seats.
- To-be-Announced, the Sponsorship of Infrastructure and EOS Resources, currently holds 2 (two) seats.
- Free 6 (six) seats to be defined, according to the project requirements and consensus with the current board.

These seats belong to their holders and they are available to transfer between them and the outside world - as long as the transfer is agreed with current board composition.

## Shares
In our system shares are distributed to contributors based on their amount of hours times their weight times.

Formula:
> HOURS * RATIO = SHARES

E.g.
> 3.5 Hours * Ratio 1 = 3.5 Shares

These shares are kept perpetually for as long as this system is in use.

This way, a contributor can have 200 shares and receive a dividend ongoing.

Should a contributor no longer contribute and therefore stop receiving further shares, his weight in dividends will slowly erode due to inflation created by ongoing contributors.

## Dividends

Dividends distributions happen in a period to be defined by the headboard but usually bi-weekly or on a monthly basis. A dividend amount is subject to be changed by the board. Without intervention, an amount to share is decided by the board, 20% of it is created as a board dividend and the remaining 80% a share dividend.

E.g.
- Sharing amount: 100 EOS
- Board Dividend: 20 EOS
- Share Dividend: 80 EOS


### Share Distribution Simulation

E.g. Period 3, Period Dividends: 1,000 EOS

Dividends Distribution => 20% = 200 EOS

Member | Seats | Received Period Dividends
---|---|---
Leo Ribeiro | 7 | 93.3333 EOS
Alex Rozgo | 6 | 80 EOS
Infra Sponsor | 2 | 26.6666 EOS

Period Distribution => 80% = 800 EOS


Member | Hour Ratio | Current Shares | Worked Hours | Accumulated Shares Balance | Received Dividends
---|---|---|---|---|---
Leo Ribeiro | 1 | 300 | 100 |  400 | 362.4009 EOS
Alex & Vertex Studio | 1 | 50 | 300 | 350 | 317.1008 EOS
Infra | 1 | 0 | 10 | 10 | 9.0600 EOS
Recurrent Community Dev A | 1 | 70 | 20 | 90 | 81.5402 EOS
Recurrent Community Dev B | 1 | 2 | 18 | 20 | 18.1200 EOS
New Community Dev C | 1 | 0 | 8 | 8 | 7.2480 EOS
New Community Dev D | 1 | 0 | 5 | 5 | 4.5300 EOS

And now, all the above participants will have accumulated shares for the next period even without any work. This scheme keeps the project motivated to constant improvements since the member's revenue will be diluted and way less while the project evolves with more and more hours by new features.

# Voting Shares
A minimum of 50% + 1 vote must be reached in order to activate an item, unless 72 hours has passed, in which case the most votes in a direction wins. Board powers include powers to revoke voting shares from other board members or completely overwrite this document.
