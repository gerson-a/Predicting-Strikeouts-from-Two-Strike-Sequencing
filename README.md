# Decoding Two Strike Pitch Sequencing in MLB

## Executive Summary

Two-strike counts represent the most critical moments of a plate appearance in Major
League Baseball. Often, the decision of which pitch to throw is influenced by the previous
pitch, with the goal of deceiving the batter through changes in velocity, movement, and
location. This is regularly referred to as 'pitch tunneling' because the two different pitches
first appear to be arriving on the same trajectory, or tunnel, before diverging. The purpose of
this report is to analyze pitch sequencing strategies in two-strike counts to identify the
patterns and metrics that most effectively result in strikeouts. Analyzing over 28,000
two-strike pitches from the 2026 season, our key finding is that the current pitch
characteristics — specifically location, fastball shape, and vertical/horizontal movement —
are the primary drivers of strikeouts, heavily overriding the differential changes from the
preceding pitch. Considering these findings, we recommend that pitchers focus on pitch location and trusting their arsenal
rather than over-relying on specific sequencing strategies. Front offices should prioritize
drafting and developing pitchers with elite velocity and fastball shapes, cultivating
command in the minor leagues when given the opportunity to work alongside professional
coaches and front offices.

## Introduction 
In the modern era of MLB, front offices and coaching staffs rely heavily on advanced
analytics to gain a competitive edge. With the advent of Statcast tracking technology, teams
have access to highly granular data on every pitch thrown. Maximizing the probability of a
strikeout in a two-strike count directly impacts run prevention and overall game outcomes,
making it a crucial research area. The primary stakeholders for these insights include
General Managers optimizing draft and development pipelines, coaching staffs devising
in-game strategies, and pitchers executing on the mound. The objective of this analysis is to
identify distinct pitch sequencing patterns in two-strike counts and evaluate how changes
between consecutive pitches influence the likelihood of a successful outcome (a strikeout).
Going into this study, our primary hypothesis was that pitchers who create greater
differences between consecutive pitches in velocity, movement, and location would generate
more successful outcomes by amplifying the tunneling effect.
