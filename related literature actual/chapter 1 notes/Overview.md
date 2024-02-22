"POS Tagging can be used to search for subject word classes from a series of sentences in news articles to find out which subject has the most significant role in influencing society"

From: 
[[Analysis of Telkom University News Subjects on Popular Indonesian News Portals Using a Combination of Hidden Markov Model (HMM) and Rule Based Methods.pdf]]

We're going with political framework.
Given that we're working with how different news reports are from one admin to another, we're gonna need a POS-tagger in order to make some sort of a mask to the words used in a report.  For example, the word 'COVID-19' wouldn't make sense to a machine trained with 2010 - 2016 data. But, it can still consider it as a health report if tagged correctly.

This [[2021.findings-acl.401.pdf|paper]] just talk about training a model to recognize biases. It cites that
> ...bias is often expressed through informational choices (Fan et al., 2019)