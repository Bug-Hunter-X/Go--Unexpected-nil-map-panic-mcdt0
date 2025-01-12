# Go: Unexpected nil map panic

This repository demonstrates a common error in Go related to uninitialized maps.  Attempting to access or modify elements of a nil map will result in a runtime panic.

The `bug.go` file shows the problematic code.  The `bugSolution.go` file provides a corrected version.

This is a subtle error that can be difficult to debug.  Always initialize your maps before use to avoid unexpected panics.