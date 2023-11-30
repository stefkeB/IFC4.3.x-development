Clothoid Transition Segment
===========================

A clothoid segment is based on the IfcClothoid where the value for the clothoid constant is specified as √L and L is the length measured from the inflection point.

```
concept {
    IfcCurveSegment:ParentCurve -> IfcClothoid
    IfcCurveSegment:SegmentStart -> IfcLengthMeasure_0
    IfcCurveSegment:SegmentLength -> IfcLengthMeasure_1
    IfcClothoid:ClothoidConstant -> IfcLengthMeasure
}
```
