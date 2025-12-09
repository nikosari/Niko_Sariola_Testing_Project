
## Summary (Summarize the bug encountered concisely)

In project creation page, there is a typo of "Create black project" instead of intended "Create blank project." 
Bug type: typo

## Steps to reproduce     

1. Login to gitlab.com
2. Open homepage gitlab.com
3. Open project creation page
4. See typo bug on the site

## What is the current bug behavior?

Bug causes project creation page to show "Create black project"

## What is the expected correct behavior?

Correct behaviour is for the project creation page to show "Create blank project"
     
## Relevant logs and/or screenshots

screenshot of bug: https://imgur.com/a/laKP0Sc

## Possible fixes
Bug found in code line:
<h3 class="gl-text-color-heading gl-text-size-h2">Create black project</h3>
Possible fix:
Instead of "black", write "blank".

## Whom do you report/ Assign To/ Tags

/label ~bug ~reproduced ~needs-investigation 
/cc @project-manager 
/assign @qa-tester

## Priority

Minor.
      
