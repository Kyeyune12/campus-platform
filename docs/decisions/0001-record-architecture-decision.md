# Architecture decision

Date: 2026/08/15
Status: Accepted

## context

Choosing between using maven and gradle, we could have taken it in a
different direction 

## Decision
I choose maven because it offers a better structure for code and has strict
setup standards.

## Consequencies
Gradle is faster but it include writing complex scripts that can break over time 
with constant changes to the code base, so I traded speed for a slow but assured 
workflow

## Alternative considered
Plain Java: Terrible for scale
Apache Ant: No in-built dependency management, requires massive procedural code 
Bazel: Introduces massive complex configurations for small to medium apps