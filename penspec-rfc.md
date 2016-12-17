# penspec
Black Box Penetration Testing Framework

## Why use PenSpec?

PenSpec aims to be the first black box penetration testing automation framework. The goal is to make automation of penetration testing a reality by maintaining a framework and DSL for writing tests that provide useful information about the attack surface of infrastructure.

### Why not just write your own tests using bash or something?

PenSpec will provide a framework that is specific to black box testing use cases that is customized for penetration testing. It will be another useful tool in a software or security engineer's toolbox.

### Why black box?

There are currently many tools out there that provide a means to write white box security audit test cases. PenSpec does not attempt to compete with these tools or replace them. White box style auditing and compliance testing can be very valuable to protect against zero days, privilege escalation, information leakage, etc. and 'CYA' (let's be honest)<br />

However, white box scanning and testing tools often provide an enormous amount of data and sometimes irrelevant results. This can and does lead to organizations ignoring the results altogether, only focusing on the low hanging fruit or prioritizing the most 'visible' vulnerabilities and skipping the more nuanced flaws that a seasoned attacker could exploit.<br />

PenSpec is designed for software and security engineers to do the following:
* provide relevant and actionable intelligence about the exploitability of a system
* ease setup, automation, upgrades by being completely agent-less
* aid in prioritization and validation of infrastructure security flaws
* provide reliable and fast feedback

### Why Ruby?

[Ruby](http://ruby-lang.org/) is an excellent language for simple code. It is fairly easy to pick up and be productive with and it is very flexible in its ability to support functional, OO and imperative programming paradigms.<br />

However, the choice of Ruby as the language for this framework is still open for discussion.

## Disclaimer

This project is still in its inception phase. This document outlines the proposed framework and attempts answer the question of 'why do we need this'.  
