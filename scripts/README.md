## Documentation

# sfa_zct()
Full Name: Zero Control Transforms
Params: None
Returns: 0
Function: Takes the Transform Matrix of each selected object and transfers it into that object's Offset Parent Matrix before resetting its local transforms. This is used in rigging to zero-out controls while maintaining their local orientation.

# sfa_rzct()
Full Name: Reverse Zero Control Transforms
Params: None
Returns: 0
Function: Performs the reverse operation of ``sfa_zct()``: transfers each object's Offset Parent Matrix into their Transform Matrix before resetting its Offset Parent Matrix. This is used in rigging to zero-out the offset parent matrix so that a controller's transformation can be changed without messing up the offset parent matrix later.