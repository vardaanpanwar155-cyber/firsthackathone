# TruthLens Design Decisions

## DP1: Feed order
- **Choice:** Sorted by urgency and risk flags first, followed by submission time.
- **Why:** In misinformation triage, high-risk unverified sensational claims require immediate community and reviewer attention compared to already verified items, preventing viral panic.

## DP2: Visibility
- **Choice:** Unverified claims remain publicly visible immediately upon submission with an explicit warning badge.
- **Why:** Complete transparency is critical in civic tech. Hiding claims during a check creates bottleneck delays; instead, flagging them clearly warns users in real-time.

## DP3: Editing
- **Choice:** Submitted claims cannot be edited by the general submitter after submission, but reviewers can append verification notes and change statuses.
- **Why:** Allowing users to edit claims post-submission breaks audit trails and integrity. Reviewers alone manage the correction workflow to maintain factual accuracy.
-