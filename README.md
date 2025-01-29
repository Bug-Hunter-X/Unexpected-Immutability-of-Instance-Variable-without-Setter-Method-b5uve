# Unexpected Immutability of Instance Variable without Setter Method in Ruby

This example demonstrates a common, yet subtle, error in Ruby related to instance variable access and modification.

In this scenario, we attempt to modify an instance variable directly from outside the class. The absence of a setter method prevents any change;  the instance variable remains immutable. This can lead to unexpected behavior and debugging challenges.