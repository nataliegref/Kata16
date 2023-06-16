
# Kata16

Make a payment system such that:
- If the payment is for a physical product, generate a packing slip for shipping.
- If the payment is for a book, create a duplicate packing slip for the royalty department.
- If the payment is for a membership, activate that membership.
- If the payment is an upgrade to a membership, apply the upgrade.
- If the payment is for a membership or upgrade, e-mail the owner and inform them of the activation/upgrade.
- If the payment is for the video “Learning to Ski,” add a free “First Aid” video to the packing slip (the result of a court decision in 1997).
- If the payment is for a physical product or a book, generate a commission payment to the agent.Now you’re faced with implementing this system. You know that they’re going to change: once the system goes live, all sorts of special cases will come out of the woodwork.

### Objectives
How can you tame these wild business rules? How can you build a system that will be flexible enough to handle both the complexity and the need for change? And how can you do it without condemming yourself to years and years of mindless support?


## Results
Made the system such that the current rules are implemented and future rules can be added, or modified