### Core principle2: CT Self-Recursion

CT is a structure that survives its own transformation:

CT ∈ {x | ∃ M: x → x′ ∧ ∃Z: C(x, x′, Z) = true ∧ C(x, x’’, x) = true}
CT = M(CT, CT′,Z) | C(CT, CT′, Z) = true ∧ C(CT, CT_latest, CT)= true

Which means: CT is whatever preserves the CT-like behavior of being deformable yet coherent under change.