A Cartesian transformation operator 2d non uniform defines a geometric transformation in two-dimensional space composed of translation, rotation, mirroring and non uniform scaling. Non uniform scaling is given by two different scaling factors:

* _SELF\IfcCartesianTransformationOperator.Scale_: the x axis scale factor
* _Scale2_: the y axis scale factor


<!-- end of short definition -->

If the _Scale_ factor (at supertype _IfcCartesianTransformationOperator_) is omitted, it defaults to 1.0. If the _Scale2_ factor is omitted, it defaults to the value of _Scale_ (the x axis scale factor).

> NOTE The scale factor (_Scl_) defined at the supertype _IfcCartesianTransformationOperator_ is used to express the calculated _Scale_ factor (normally x axis scale factor).

> HISTORY New entity in IFC2x.

## Attributes

### Scale2
The scaling value specified for the transformation along the axis 2. This is normally the y scale factor.

### Scl2
The derived scale S(2) of the transformation along the axis 2 (normally the y axis), equal to Scale2 if that exists, or equal to the derived Scl1 (normally the x axis scale factor) otherwise.

## Formal Propositions

### Scale2GreaterZero
The derived scaling Scl2 shall be greater than zero.
