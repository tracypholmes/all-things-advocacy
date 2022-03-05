# Going GitOps From a Terraform Tinkerer’s Perspective

## Abstract

There’s this buzzword going around lately: GitOps. What exactly IS GitOps? The core principles of GitOps are as follows:

1. The system is described in a declarative manner. 
1. The definition of the system is versioned and audited. (This is typically Git.) 
1. A software agent automatically pulls the Git state and matches the platform state. 
1. The state is continuously reconciled. This means any changes happening in Git should also be reflected in the system, and vice-versa.

Terraform, a popular IaC tool natively has the 1st requirement (declarative format). However, it doesn’t really satisfy the other three (Terraform has its own state, the proverbial right hand at times doesn’t know what the left hand is doing, etc.) This talk will explore tinkering with Terraform to make it work with GitOps core principles, any pros, and cons, and possible alternatives that natively Just Work™️.
