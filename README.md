# A-A_testing
Carried out A/A-testing of mobile app using FPR metric (False Positive Rate). We know that traffic splitting system is broken. We need to check this out and find its reasons.

Results:
  1. After aggregation I found out that the conversion to the purchase of mobile app ver. 2.8.0 is much smaller that the ones of other versions (FPR ~ 0.93).
  2. T-test for users with mobile app of this version from experiment groups 0 and 1 showed p-value of 0.0.
  3. Final A/A-testing showed FPR ~ 0.05 which is what we need.
