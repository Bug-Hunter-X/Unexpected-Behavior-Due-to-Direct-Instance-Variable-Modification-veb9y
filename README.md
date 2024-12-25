# Ruby Bug: Unexpected Behavior from Direct Instance Variable Modification

This example demonstrates a common issue in Ruby where directly modifying instance variables using `instance_variable_set` can lead to unforeseen consequences.  The problem arises when this method is used to bypass the intended object interface, potentially violating encapsulation and making the code less predictable.

The solution shows how to address this by relying on appropriate methods to modify the internal state of an object, preserving code integrity and maintainability.