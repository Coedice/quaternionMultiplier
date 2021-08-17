# quaternionMultiplier
A Turing Machine built with Tuatara that simplifies quaternion products.

Input tapes must match the regular expression `/^[PM]?[IJK]+/` to be valid.
Results to correct inputs will always match the regular expression `/M?[IJK]/`.

Input alphabet:
- M: Negative
- P: Positive
- I, J, K: Basic quaternions
