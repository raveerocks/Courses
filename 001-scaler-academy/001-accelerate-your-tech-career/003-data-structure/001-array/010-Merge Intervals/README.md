# Merge Intervals

## Problem Description

Given a set of non-overlapping intervals, insert a new interval into the intervals (merge if necessary).

***You may assume that the intervals were initially sorted according to their start times.***

Make sure the returned intervals are also sorted.

## Example 1
Given intervals `[1,3]`,`[6,9]` insert and merge `[2,5]` would result in `[1,5]`,`[6,9]`.

## Example 2
Given intervals `[1,2]`,`[3,5]`,`[6,7]`,`[8,10]`,`[12,16]`, insert and merge `[4,9]` would result in `[1,2]`,`[3,10]`,`[12,16]`.

## Example Explanation

This is because the new interval `[4,9]` overlaps with `[3,5]`,`[6,7]`,`[8,10]`

