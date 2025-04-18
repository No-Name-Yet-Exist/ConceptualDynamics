### Sub Principle 1: Permission to Conditional Modification (PCM):

You can modify the self recursion of CT as long as you maintain CT ~ CT’ 

For example, you can add Z in C(CT, CT_latest, CT) to ensure the local continuity of CT 
CT = M(CT, CT′,Z) | C(CT, CT′, Z) = true ∧ C(CT, CT_latest, CT)= true

Or you can add a new function like a stabilizing function. This also extends to other parts of CT.