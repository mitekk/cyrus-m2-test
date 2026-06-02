# SYNTHETIC PER-PROJECT REVIEWER OVERRIDE — Phase 5 B2 verification only

This file is a temporary synthetic override used to verify the per-project reviewer-prompt precedence logic added to `terraform/github.tf` at Phase 5 Step B2. It is **not** intended to ship; the verification step deletes it and re-applies to revert `mitekk/cyrus-m2-test`'s `.github/reviewer-prompt.md` back to the global `prompts/_global/reviewer.md` content.

If you see this file in `master` (or worse, in a cyrus-m2-test PR), the synthetic-override cleanup step at Phase 5 Step B2 was skipped. Delete the file and re-apply `terraform`.

(Synthetic divergence marker so the `tf plan` diff is unambiguous against the global prompt.)

