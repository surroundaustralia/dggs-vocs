Markdown documentation created by [pyLODE](http://github.com/rdflib/pyLODE) 

# DGGS Abstract Sepcification 2.0 Terms and definitions
### A taxonomy

## Metadata
* **URI**
  * `https://w3id.org/dggs/as-terms`
* **Publisher(s)**
  * [Open Geospatial Consortium](https://www.ogc.org)
* **Creators(s)**
  * [Open Geospatial Consortium](https://www.ogc.org)
* **Contributor(s)**
  * None
* **Created**
  * 2020-08-21
* **Modified**
  * 2020-08-21
* **Version URI**
  * [1.0](https://w3id.org/dggs/as-terms/1.0)

* **Taxonomy RDF**
  * RDF ([as-terms.ttl](turtle))
### Description
<p>Terms, represented as SKOS Concepts, from Section 4 of the Discrete Global Grid Abstract Specification, version 2.0.</p>


## Table of Contents
1. [Object Concepts](#concepts)
1. [Namespaces](#namespaces)
1. [Legend](#legend)


## Concepts
* [boundary](https://w3id.org/dggs/as-terms/4-1)
* [datum](https://w3id.org/dggs/as-terms/4-10)
* [datum ensemble](https://w3id.org/dggs/as-terms/4-11)
* [discrete global grid](https://w3id.org/dggs/as-terms/4-12)
* [discrete global grid system](https://w3id.org/dggs/as-terms/4-13)
* [duration](https://w3id.org/dggs/as-terms/4-14)
* [dynamic coordinate reference system](https://w3id.org/dggs/as-terms/4-15)
* [dynamic reference frame](https://w3id.org/dggs/as-terms/4-16)
* [error budget](https://w3id.org/dggs/as-terms/4-17)
* [feature](https://w3id.org/dggs/as-terms/4-18)
* [feature type](https://w3id.org/dggs/as-terms/4-19)
* [cell](https://w3id.org/dggs/as-terms/4-2)
* [geodetic coordinate reference system](https://w3id.org/dggs/as-terms/4-20)
* [geographic coordinate reference system](https://w3id.org/dggs/as-terms/4-21)
* [geographic identifier](https://w3id.org/dggs/as-terms/4-22)
* [geometric primitive](https://w3id.org/dggs/as-terms/4-23)
* [globe](https://w3id.org/dggs/as-terms/4-24)
* [grid](https://w3id.org/dggs/as-terms/4-25)
* [hierarchy](https://w3id.org/dggs/as-terms/4-26)
* [initial discrete global grid](https://w3id.org/dggs/as-terms/4-27)
* [interoperability](https://w3id.org/dggs/as-terms/4-28)
* [instant](https://w3id.org/dggs/as-terms/4-29)
* [cell refinement](https://w3id.org/dggs/as-terms/4-3)
* [interval](https://w3id.org/dggs/as-terms/4-30)
* [location](https://w3id.org/dggs/as-terms/4-31)
* [observation](https://w3id.org/dggs/as-terms/4-32)
* [parent cell](https://w3id.org/dggs/as-terms/4-33)
* [period](https://w3id.org/dggs/as-terms/4-34)
* [period identifier](https://w3id.org/dggs/as-terms/4-35)
* [quantization](https://w3id.org/dggs/as-terms/4-36)
* [refinement level](https://w3id.org/dggs/as-terms/4-37)
* [refinement ratio](https://w3id.org/dggs/as-terms/4-38)
* [sibling cell](https://w3id.org/dggs/as-terms/4-39)
* [child cell](https://w3id.org/dggs/as-terms/4-4)
* [simple](https://w3id.org/dggs/as-terms/4-40)
* [spatial reference](https://w3id.org/dggs/as-terms/4-41)
* [spatio-temporal reference](https://w3id.org/dggs/as-terms/4-42)
* [spatio-temporal coordinate reference system](https://w3id.org/dggs/as-terms/4-43)
* [static coordinate reference system](https://w3id.org/dggs/as-terms/4-44)
* [static reference frame](https://w3id.org/dggs/as-terms/4-45)
* [temporal coordinate system](https://w3id.org/dggs/as-terms/4-46)
* [temporal coordinate reference system](https://w3id.org/dggs/as-terms/4-47)
* [tessellation](https://w3id.org/dggs/as-terms/4-48)
* [value](https://w3id.org/dggs/as-terms/4-49)
* [class](https://w3id.org/dggs/as-terms/4-5)
* [zonal query](https://w3id.org/dggs/as-terms/4-50)
* [zonal identifier](https://w3id.org/dggs/as-terms/4-51)
* [zone](https://w3id.org/dggs/as-terms/4-52)
* [compound coordinate reference system](https://w3id.org/dggs/as-terms/4-6)
* [coordinate reference system](https://w3id.org/dggs/as-terms/4-7)
* [coordinate system](https://w3id.org/dggs/as-terms/4-8)
* [data type](https://w3id.org/dggs/as-terms/4-9)

### boundary
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-1`
Preferred Labels |boundary (en)<br />
Definitions |['set that represents the limit of an entity']<br />
Scope Notes |Boundary is most commonly used in the context of geometry, where the set is a collection of points or a collection of objects that represent those points. In other domains, the term is used metaphorically to describe the transition between an entity and the rest of its domain of discourse.<br />
### datum
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-10`
Preferred Labels |datum (en)<br />
Definitions |['reference frame parameter or set of parameters that realize the positions of the origin, the scale, and the orientation of a coordinate system (Clause 4.8)']<br />
### datum ensemble
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-11`
Preferred Labels |datum ensemble (en)<br />
Definitions |['group of multiple realizations of the same terrestrial or vertical reference system that, for approximate spatial referencing purposes, are not significantly different']<br />
Scope Notes |Datasets referenced to the different realizations within a datum ensemble may be merged without coordinate transformation.<br />‘Approximate’ is for users to define but typically is in the order of under 1 decimetre but may be up to 2 metres.<br />
Examples |`“WGS 84” as an undifferentiated group of realizations including WGS 84 (TRANSIT), WGS 84 (G730), WGS 84 (G873), WGS 84 (G1150), WGS 84 (G1674) and WGS 84 (G1762). At the surface of the Earth these have changed on average by 0.7 m between the TRANSIT and G730 realizations, a further 0.2 m between G730 and G873, 0.06 m between G873 and G1150, 0.2 m between G1150 and G1674 and 0.02 m between G1674 and G1762).`<br /><br />
### discrete global grid
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-12`
Preferred Labels |discrete global grid (en)<br />
Definitions |['<DGGS> set of cells (Clause 4.2) at the same refinement level (Clause 4.37), that uniquely and completely cover a globe']<br />
Scope Notes |the configuration of the set of cells comprising a discrete global grid satisfy at least one grid constraint in the DGG_GridConstraint codelist<br />the set of cell zonal identifiers (Clause 4.51) comprising a discrete global grid form a single Zone Class with its associated refinement level (Clause 4.37).<br />
### discrete global grid system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-13`
Preferred Labels |discrete global grid system (en)<br />
Definitions |['DGGS integrated system comprising a hierarchy (Clause 4.26) of discrete global grids (Clause 4.12), spatio-temporal referencing (Clause 4.42) by zonal identifiers (Clause 4.51) and functions for quantization (Clause 4.36), zonal query (Clause 4.50), and interoperability (Clause 4.28)']<br />
### duration
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-14`
Preferred Labels |duration (en)<br />
Definitions |['non-negative quantity of time equal to the difference between the final and initial instants (Clause 4.29) of a time interval (Clause 4.30)']<br />
Scope Notes |The exact duration of a time scale unit depends on the time scale used. For example, the durations of a year, month, week, day, hour or minute, may depend on when they occur [in a Gregorian calendar, a calendar month can have a duration of 28, 29, 30, or 31 days; in a 24-hour clock, a clock minute can have a duration of 59, 60, or 61 seconds, etc.]. Therefore, the exact duration can only be evaluated if the exact duration of each is known.<br />This definition is closely related to NOTE 1 of the terminological entry “duration” in IEC 60050-113:2011, 113-01-13.<br />For the term “duration”, expressions such as “time” or “time interval” are often used, but the term “time” is not recommended in this sense and the term “time interval” is deprecated in this sense to avoid confusion with the concept of “time interval”.<br />The duration is one of the base quantities in the International System of Quantities (ISQ) on which the International System of Units (SI) is based. The term “time” instead of “duration” is often used in this context and also for an infinitesimal duration.<br />
### dynamic coordinate reference system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-15`
Preferred Labels |dynamic coordinate reference system (en)<br />
Definitions |['coordinate reference system (Clause 4.7) that has a dynamic reference frame (Clause 4.16)']<br />
Scope Notes |Metadata for a dataset referenced to a dynamic coordinate reference system should include coordinate epoch information.<br />Coordinates of points on or near the crust of the Earth that are referenced to a dynamic coordinate reference system may change with time, usually due to crustal deformations such as tectonic motion and glacial isostatic adjustment.<br />
### dynamic reference frame
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-16`
Preferred Labels |dynamic reference frame (en)<br />
Definitions |['dynamic datum reference frame (Clause 4.10) in which the defining parameters include time evolution']<br />
Scope Notes |The defining parameters that have time evolution are usually a coordinate set.<br />
### error budget
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-17`
Preferred Labels |error budget (en)<br />
Definitions |['<metric> statement of or methodology for describing the nature and magnitude of the errors which affect the results of a calculation']<br />
### feature
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-18`
Preferred Labels |feature (en)<br />
Definitions |['abstraction of real-world phenomena']<br />
Scope Notes |A feature may occur as a type or an instance. In this document, feature instance is meant unless otherwise specified.<br />
### feature type
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-19`
Preferred Labels |feature type (en)<br />
Definitions |['class (Clause 4.5) of features (Clause 4.18) having common characteristics']<br />
### cell
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-2`
Preferred Labels |cell (en)<br />
Definitions |['<DGGS> spatial, spatio-temporal or temporal unit of geometry with dimension greater than 0, associated with a unique zonal identifier (Clause 4.51)']<br />
Scope Notes |Cells are the primary container for storing and retrieving data within a DGGS implementation.<br />The zonal identifier (Clause 4.51) of a cell provides the coordinates of a representative position for the cell, and all feature geometry is represented by sets of cells.<br />DGGS may instantiate cells by reference to their zonal identifier (Clause 4.51), for instance in databases or through tile nomenclature, and by their geometry, for instance through membership of a grid.<br />All cells within a DGGS share the dimensionality of the DGGS, and DGGS with dimensionality of 0, are not supported.<br />
### geodetic coordinate reference system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-20`
Preferred Labels |geodetic coordinate reference system (en)<br />
Definitions |['three-dimensional coordinate reference system (Clause 4.7) based on a geodetic reference frame and having either a three-dimensional Cartesian or a spherical coordinate system']<br />
Scope Notes |In this document a coordinate reference system (Clause 4.7) based on a geodetic reference frame and having an ellipsoidal coordinate system is geographic.<br />
### geographic coordinate reference system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-21`
Preferred Labels |geographic coordinate reference system (en)<br />
Definitions |['coordinate reference system (Clause 4.7) that has a geodetic reference frame and an ellipsoidal coordinate system']<br />
### geographic identifier
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-22`
Preferred Labels |geographic identifier (en)<br />
Definitions |['spatial reference (Clause 4.41) in the form of a label or code that identifies a location (Clause 4.31)']<br />
Examples |`“Spain” is an example of a label (country name); “SW1P 3AD” is an example of a code (postcode).`<br /><br />
### geometric primitive
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-23`
Preferred Labels |geometric primitive (en)<br />
Definitions |['geometric object representing a single, connected, homogeneous (isotropic) element of space']<br />
Scope Notes |Geometric primitives are non-decomposed objects that present information about geometric configuration. They include points, curves, surfaces, and solids. Many geometric objects behave like primitives (supporting the same interfaces defined for geometric primitives) but are actually composites composed of some number of other primitives. General collections may be aggregates and incapable of acting like a primitive (such as the lines of a complex network, which is not connected and thus incapable of being traceable as a single line). By this definition, a geometric primitive is topological open, since the boundary points are not isotropic to the interior points. Geometry is assumed to be closed. For points, the boundary is empty.<br />
### globe
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-24`
Preferred Labels |globe (en)<br />
Definitions |['<DGGS> celestial body']<br />
Scope Notes |In this document globe is used in its most general form to refer to any celestial body that may be referenced by a DGGS. When a specific body, such as the Earth is referred to, an explicit term is used.<br />
### grid
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-25`
Preferred Labels |grid (en)<br />
Definitions |['network composed of two or more sets of curves in which the members of each set intersect the members of the other sets in an algorithmic way']<br />
Scope Notes |The curves partition a space into grid cells.<br />
### hierarchy
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-26`
Preferred Labels |hierarchy (en)<br />
Definitions |['<DGGS> organization and ranking of successive levels of cell refinement (Clause 4.3) of discrete global grids (Clause 4.12)']<br />
### initial discrete global grid
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-27`
Preferred Labels |initial discrete global grid (en)<br />
Definitions |['<DGGS> discrete global grid tessellation created by circumscribing a defined path along the chosen surface model of the Earth between the vertices of the scaled base unit polyhedron']<br />
### interoperability
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-28`
Preferred Labels |interoperability (en)<br />
Definitions |['capability to communicate, execute programs, or transfer data among various functional units in a manner that requires the user to have little or no knowledge of the unique characteristics of those units']<br />
Scope Notes |in this standard interoperability specifically refers to functions that initiate and process transfers of data from a DGGS system.<br />
### instant
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-29`
Preferred Labels |instant (en)<br />
Definitions |['<DGGS> temporal geometry primitive representing a point in time']<br />
Scope Notes |On temporal coordinate systems as specified in (Clause 4.46), the temporal geometric primitives (Clause 4.23) instant and interval (Clause 4.30) are the equivalent of points and lines as specified in (ISO 19107:2019).<br />
### cell refinement
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-3`
Preferred Labels |cell refinement (en)<br />
Definitions |['<DGGS> process of subdividing parent cells (Clause 4.33) into descendant child cells (Clause 4.4) using a specified refinement ratio (Clause 4.38) and suite of refinement strategies']<br />
Scope Notes |Cell refinement methods may result in child cells that each have a single parent or that have multiple parents.<br />Iterative application of cell refinements creates a hierarchy of descendant discrete global grids (Clause 4.12).<br />
### interval
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-30`
Preferred Labels |interval (en)<br />
Definitions |['<DGGS> temporal geometry primitive representing a line in time']<br />
Scope Notes |On temporal coordinate systems as specified in (Clause 4.46), the temporal geometric primitives (Clause 4.23) instant (Clause 4.29) and interval are the equivalent of points and lines as specified in (ISO 19107:2019).<br />
### location
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-31`
Preferred Labels |location (en)<br />
Definitions |['particular place or position']<br />
Scope Notes |In the context of DGGS, locations have dimension greater than one, and so are not points.<br />A location identifies a geographic place.<br />
Examples |`“Madrid”, “SW1P 3AD”.`<br /><br />
### observation
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-32`
Preferred Labels |observation (en)<br />
Definitions |['act of measuring or otherwise determining the value (Clause 4.49) of a property']<br />
### parent cell
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-33`
Preferred Labels |parent cell (en)<br />
Definitions |['<DGGS> cell in a higher refinement level of discrete global grid with immediate descendants']<br />
Scope Notes |parent cells either overlap or contain their child cells (Clause 4.4).<br />
### period
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-34`
Preferred Labels |period (en)<br />
Definitions |['<DGGS> particular era or span of time']<br />
Scope Notes |Periods are intervals (Clause 4.30) named with a period identifier (Clause 4.35)<br />
### period identifier
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-35`
Preferred Labels |period identifier (en)<br />
Definitions |['<DGGS> temporal reference in the form of a label or code that identifies a period (Clause 4.34)']<br />
Scope Notes |Period identifiers are the temporal equivalent of geographic identifiers (Clause 4.22) as specified in (ISO 19112:2019)<br />
### quantization
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-36`
Preferred Labels |quantization (en)<br />
Definitions |['<DGGS> function assigning data from external sources to cell values']<br />
### refinement level
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-37`
Preferred Labels |refinement level (en)<br />
Definitions |['<DGGS> numerical order of a discrete global grid (Clause 4.12) in the tessellation sequence']<br />
Scope Notes |The tessellation with the smallest number of cells has a refinement level = 0.<br />
### refinement ratio
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-38`
Preferred Labels |refinement ratio (en)<br />
Definitions |['<DGGS> ratio of the number of child cells to parent cells']<br />
Scope Notes |A positive integer ratio n refinement of DGGS parent cells yield n times as many child cells as parent cells.<br />For a two-dimensional DGGS (as defined in this document) this is the surface area ratio.<br />In DGGS literature [10] the term aperture has been used instead of refinement ratio. Refinement ratio is preferred because it is clearer in meaning to audiences outside the early DGGS community.<br />
### sibling cell
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-39`
Preferred Labels |sibling cell (en)<br />
Definitions |['<DGGS> cell in a discrete global grid with the same parent cell (Clause 4.33)']<br />
Scope Notes |all the child cells (Clause 4.4) of a parent cell (Clause 4.33) are each others’ sibling cells (Clause 4.39).<br />
### child cell
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-4`
Preferred Labels |child cell (en)<br />
Definitions |['<DGGS> immediate descendant of a parent cell']<br />
Scope Notes |child cells are either within a single parent cell (Clause 4.33) or overlapped by multiple parent cells<br />
### simple
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-40`
Preferred Labels |simple (en)<br />
Definitions |['<topology, geometry> homogeneous (all points have isomorphic neighborhoods) and with a simple boundary']<br />
Scope Notes |The interior is everywhere locally isomorphic to an open disc in a Euclidean coordinate space of the appropriate dimension Dn = {P|‖P‖ < 1.0}. The boundary is a dimension one smaller. This essentially means that the object does not intersect nor touch itself. Generally used for a curve that does not cross not touch itself with the possible exception of boundary points. Simple closed curves are isomorphic to a circle.<br />
### spatial reference
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-41`
Preferred Labels |spatial reference (en)<br />
Definitions |['system for identifying position in the real world']<br />
Scope Notes |This may take the form of a label, code or coordinate tuple.<br />
### spatio-temporal reference
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-42`
Preferred Labels |spatio-temporal reference (en)<br />
Definitions |['system for identifying position in the real world that may include time']<br />
Scope Notes |This may take the form of a label, code or coordinate tuple.<br />
### spatio-temporal coordinate reference system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-43`
Preferred Labels |spatio-temporal coordinate reference system (en)<br />
Definitions |['compound coordinate reference system (Clause 4.7) in which one constituent coordinate reference system (Clause 4.7) is a spatial coordinate reference system (Clause 4.7) and one is a temporal coordinate reference system (Clause 4.47)']<br />
### static coordinate reference system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-44`
Preferred Labels |static coordinate reference system (en)<br />
Definitions |['coordinate reference system (Clause 4.7) that has a static reference frame (Clause 4.45)']<br />
Scope Notes |Coordinates of points on or near the crust of the Earth that are referenced to a dynamic coordinate reference system do not change with time.<br />Metadata for a dataset referenced to a static coordinate reference system does not require coordinate epoch information.<br />
### static reference frame
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-45`
Preferred Labels |static reference frame (en)<br />
Definitions |['static datum eference frame (Clause 4.10) in which the defining parameters exclude time evolution']<br />
### temporal coordinate system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-46`
Preferred Labels |temporal coordinate system (en)<br />
Definitions |['<geodesy> one-dimensional coordinate system where the axis is time']<br />
### temporal coordinate reference system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-47`
Preferred Labels |temporal coordinate reference system (en)<br />
Definitions |['coordinate reference system (Clause 4.7) based on a temporal datum']<br />
### tessellation
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-48`
Preferred Labels |tessellation (en)<br />
Definitions |['partitioning of a space into a set of conterminous subspaces having the same dimension as the space being partitioned']<br />
Scope Notes |A tessellation composed of congruent regular polygons or polyhedra is a regular tessellation. One composed of regular, but non-congruent polygons or polyhedra is a semi-regular tessellation. Otherwise the tessellation is irregular. Tessellations on curved surfaces cannot be congruent, so all tessellations in DGGS are either semi-regular or irregular.<br />
Examples |`Graphic examples of tessellations may be found in Figures 11, 13, 20, and 22 of ISO 19123:2005.`<br /><br />
### value
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-49`
Preferred Labels |value (en)<br />
Definitions |['element of a type domain']<br />
Scope Notes |A data value is an instance of a datatype, a value without identity.<br />A value can use one of a variety of scales including nominal, ordinal, ratio and interval, spatial and temporal. Primitive datatypes can be combined to form aggregate datatypes with aggregate values, including vectors, tensors and images.<br />A value considers a possible state of an object within a class (Clause 4.5) or type (domain).<br />
### class
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-5`
Preferred Labels |class (en)<br />
Definitions |['description of a set of objects that share the same attributes, operations, methods, relationships, and semantics']<br />
Scope Notes |A class may use a set of interfaces to specify collections of operations it provides to its environment. The term was first used in this way in the general theory of object-oriented programming, and later adopted for use in this same sense in UML.<br />
### zonal query
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-50`
Preferred Labels |zonal query (en)<br />
Definitions |['<DGGS> geometry or topology function using a cell’s zonal identifiers (Clause 4.51) to specify geometry']<br />
Scope Notes |ISO 19107:2019 specifies a suite of geometry and topology functions in the Query2D and Query3D classes, where geometry elements used in each function’s parameters are described by sets of coordinates. In DGGS all geometry can be referenced as sets of cells (Clause 4.2) represented solely by a list (or set) of their zonal identifiers (Clause 4.51). This standard specifies zoneQuery to implement the operations in both Query2D and Query3D using zonal identifiers (Clause 4.51) to reference each operation’s source and target geometry.<br />
### zonal identifier
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-51`
Preferred Labels |zonal identifier (en)<br />
Definitions |['<DDGS> spatio-temporal reference (Clause 4.42) in the form of a label or code that identifies a zone (Clause 4.52)']<br />
Scope Notes |A zonal identifier may be a geographic identifier (Clause 4.22), period identifier (Clause 4.35), or a compound of the two.<br />
### zone
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-52`
Preferred Labels |zone (en)<br />
Definitions |['<DGGS> particular region of space-time']<br />
Scope Notes |A zone may be either a single zonal primitive or a compound zone comprising one location (Clause 4.31) and one period (Clause 4.34).<br />Zones may be spatial, temporal, or spatio-temporal, and may be regions of space-time associated with any celestial body.<br />The primitives of zone are location (Clause 4.31) and period (Clause 4.34).<br />
### compound coordinate reference system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-6`
Preferred Labels |compound coordinate reference system (en)<br />
Definitions |['coordinate reference system (Clause 4.7) using at least two independent coordinate reference systems (Clause 4.7)']<br />
Scope Notes |Coordinate reference systems (Clause 4.7) are independent of each other if coordinate values in one cannot be converted or transformed into coordinate values in the other.<br />
### coordinate reference system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-7`
Preferred Labels |coordinate reference system (en)<br />
Definitions |['coordinate system that is related to an object by a datum (Clause 4.10)']<br />
Scope Notes |Geodetic and vertical datums are referred to as reference frames.<br />For geodetic and vertical datums (Clause 4.10), the object will be the Earth. In planetary applications, geodetic and vertical reference frames may be applied to other celestial bodies.<br />
### coordinate system
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-8`
Preferred Labels |coordinate system (en)<br />
Definitions |['set of mathematical rules for specifying how coordinates are to be assigned to points']<br />
### data type
Property | Value
--- | ---
URI | `https://w3id.org/dggs/as-terms/4-9`
Preferred Labels |data type (en)<br />
Definitions |['specification of a value (Clause 4.49) domain with operations allowed on values in this domain']<br />
Scope Notes |Data types include primitive predefined types and user-definable types. All instances of a data type lack identity.<br />
Examples |`Integer, Real, Boolean, String, Date (conversion of a date into a series of codes).`<br /><br />

## Namespaces
* **:**
  * `https://w3id.org/dggs/as-terms/`
* **cs**
  * `https://w3id.org/dggs/as-terms`
* **dcterms**
  * `http://purl.org/dc/terms/`
* **owl**
  * `http://www.w3.org/2002/07/owl#`
* **rdf**
  * `http://www.w3.org/1999/02/22-rdf-syntax-ns#`
* **rdfs**
  * `http://www.w3.org/2000/01/rdf-schema#`
* **sdo**
  * `https://schema.org/`
* **skos**
  * `http://www.w3.org/2004/02/skos/core#`
* **xsd**
  * `http://www.w3.org/2001/XMLSchema#`

## Legend
* Collections: cl
* Concepts: cp