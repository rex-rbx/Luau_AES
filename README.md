# Luau_AES

This is an AES implementation in pure Luau. Currently only 256-bit keys encryption keys are supported along with the ECB block cypher mode. If you review the code, feel free to give me some feedback. If you find a bug, would like a feature, or have a question please file an issue.

We are using bit32 in this code;
If your using non luau; then check my native_bit32 repo out! Itll sure help!

This implementation assumes that the machine running the encryption/decryption is secure and makes no attempt to cleanse used memory or prevent timing attacks. Information passing through may be very vulnerable in some applications due to the way memory is allocated and system memory visability.
