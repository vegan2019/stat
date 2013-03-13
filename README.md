# Statistics

Pure [Go](http://www.golang.org) implementation of the [GSL Statistics library](http://www.gnu.org/software/gsl/manual/html_node/Statistics.html).

For the API overview see [Godoc](http://godoc.org/github.com/grd/stat).

Why create this repository when there is also "github.com/grd/statistics" ?
Three reasons:
- Updated API. The interfaces are simpler and the types are more conformal to Go.
- License changed from GPL v2 to v3 (GNU GSL 1.15 uses GPL v3).
- Package name "stat" is shorter than "statistics", while retaining logic.

### API Interfaces:
- It uses interfaces for the data access. So different data types can be used.
- Two datatypes are pre-defined: Float64 and Int64.
- For sampling purposes there is a Strider type provided.

Testing 100% pass. Testing covers the complete functionality.  
Tested on Debian6 32-bit and Windows 7 64-bit.

