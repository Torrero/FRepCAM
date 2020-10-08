# FRepCAM
Computer-aided Manufacturing (CAM) system for Function Represented models.

This project is CAM system for Function Representation approach in 3D modeling.  Function Representation (FRep) is geometric representation in an implicit form, where the object is represented by a mathematical function. This method has a significant potential for the area of Additive Manufacturing. 

The opensource project [hyperfun.org] is devoted to the Function Representation.

FRepCAM system was implemented using c++17 programming language and Qt framework.

FRepCAM software modules are available on request.

The following paper describes the FRepCAM system:

Dmitry Popov, Evgenii Maltsev, Oleg Fryazinov, Alexander Pasko, Iskander Akhatov,
Efficient contouring of functionally represented objects for additive manufacturing,
Computer-Aided Design,
Volume 129,
2020,
102917,
ISSN 0010-4485,
https://doi.org/10.1016/j.cad.2020.102917.
(http://www.sciencedirect.com/science/article/pii/S001044852030110X)
Abstract: Functionally (implicitly) defined 3D objects allow us to quite easily model parts with complex topology such as lattices and organic-like structures with a high level of flexibility. Previous works in this area are based on the direct generation of CNC programs for the 3D printing of these objects and are backed by the growing support for this input format from hardware manufacturers. Efficient contouring of functionally defined models, however, is not an easy task. In this paper, we develop an algorithm for contour extraction of implicitly defined objects for direct additive manufacturing (AM). By comparing various adaptive and exhaustive (non-adaptive) methods of the function representation contouring for AM (FRepCAM), we make a set of recommendations for its usage depending on the specific resolution of the printer. In particular, we use a novel criterion based on affine arithmetic to maintain efficiency while preserving the robustness of the contouring process. The techniques mentioned were evaluated for algebraic and non-algebraic solids and heterogeneous models under a resolution that is comparable with that of current AM technology. The results show that the chosen adaptation criteria allow us to efficiently obtain a contour for complex models and generally outperform those of traditional algorithms based on exhaustive enumeration, especially for high-resolution contouring. In addition, the results present proof of the printability of implicitly defined objects with different 3D printing techniques.
Keywords: Function representation; Level set; Interval arithmetic; Affine arithmetic; Direct fabrication; Adaptive contouring
