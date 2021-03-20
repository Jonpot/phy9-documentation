---
description: 'When adding a new class section, it is necessary to create a few roles first.'
---

# Creating Roles

## Creating @&lt;Professor&gt; Student Roles

This role should be ranked higher than @Student but lower than @TA on the role hierarchy. These roles should be given only one permission: "Change Nickname."

Once this role has been created, the message in \#class-selection will need to be updated to support this new section. The associated reaction role feature of Carl-bot will also need to be updated through the [https://carl.gg/](https://carl.gg/) portal.

**Note** that this may eventually need to be changed if the physics departments stagger exams. Currently the Exam Protocol expects all @Students to take an exam at the same time. If this changes, @Students should lose the ability to send messages, and that permission should be granted with the @&lt;Professor&gt; Student role.

## Creating @&lt;Professor&gt; Roles

This role should be ranked higher than @TA but lower than @Professor on the role hierarchy. These roles should be given only one permission: "Change Nickname."

