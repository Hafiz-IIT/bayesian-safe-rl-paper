# Method

Represent a predicted transition as (mean, uncertainty radius). Compute a conservative upper/lower interval and compare it with an explicit safety limit. Return ALLOW when the upper bound is safe, VERIFY when the interval crosses the boundary, and BLOCK when even the lower bound is unsafe.