# WGCCRE

### About

This is a project implementing several reports by the Working Group on Cartographic Coordinates and Rotational Elements for determining the orientation of different astronomical bodies.

At the moment it currently partially-implements reports 2015 and 2009, providing methods to compute the orientation of each of the 8 planets in the solar system, alongside Sol and Earth's moon. It also includes a utility for converting the rotation to be compatible with VSOP87, if needed.

The implementation is heavily-templated and suitable for use with scalar types of varying precision.

It is currently written in such a way that it returns the orientations as euler angles (degrees), represented as arrays of 3 elements each. However, the implementation can easily be converted to return a different type should your project require.

If you find a bug or have a feature-request, please raise an issue.

### Instructions

The implementation is header-only and written in templated C++17. You should not need to make any adjustments to your project settings or compiler flags. 

Simply include it in your project and you are ready to start!

### Note

If you intend to do anything more advanced than amateur astronomy, there exist far more precise solutions, such as those provided by NASA JPL, the IAU Minor Planets Centre, and  the IERS.

This project is also in no way associated with the IAU or WGCCRE. Please refer to the official sources for the most up-to-date reports and errata.
