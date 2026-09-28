# Reflection: singmann_afex

afex shows a cyclical pattern: repeated bursts of activity followed by quiet stretches, 
with four gaps of three or more months, tied for the most of any project in this set.

The longest gap (2023-06 to 2023-12, 7 months) was easy to interpret as the reason for the 
recovery is stated explicitly. PR #124 says the ggplot2 team ran a reverse-dependency 
check ahead of their 3.5.0 release and found that "the prospective ggplot2 3.5.0 would 
break afex," with that release scheduled for February 12. The pre-gap commits themselves 
(routine CI/test maintenance by maintainer Henrik Singmann and contributor mariusbarth) 
show no sign of trouble on their own.

The fix itself was authored by Teun van den Brand, a ggplot2 developer and not a regular
afex contributor, so the recovery was driven by someone new, though Henrik Singmann (the
long-standing maintainer) merged it and picked back up CRAN-prep work right afterward.

**Current status:** Inactive (last GitHub commit 2025-12-14, more than 6 months before the
assignment's cutoff).
