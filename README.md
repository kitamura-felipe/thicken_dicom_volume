# thicken_dicom_volume
Simple algorithm to reslice CT or MR volumes into thicker SliceThicknesses and SpacingBetweenSlices

### This is a simple algorithm to increase (only) the Spacing Between Slices (0018, 0088) of CT scans.
### It assumes the Slice Thickness is equal to Spacing Between Slices.
### Otherwise, it calculates only an approximation of the real result, which may also be useful.
