==============================

Saxon-HE 9.5 is the latest major release of the open-source edition of Saxon. 
It is available for both the Java and .NET platforms.

The current maintenance release is Saxon-HE 9.5.1.10.

The documentation for Saxon is at http://www.saxonica.com/documentation/
and includes a detailed list of changes for each release.

For the Java platform, download file SaxonHE9-5-1-10J.zip. Installation instructions are at:

http://www.saxonica.com/documentation/index.html#!about/installationjava

For the .NET platform, download file SaxonHE9-5-1-10N-setup.exe.
Installation instructions are at:

http://www.saxonica.com/documentation/index.html#!about/installationdotnet

The file saxon-resources9-5.zip contains documentation, sample files, test drivers and other miscellaneous resources. 
It is common to both platforms, and is not normally updated when new maintenance releases appear.

The file saxon9-5-1-10source.zip contains source code for both platforms; a new version is produced with each
maintenance release. Source code with the latest patches can also be obtained from a Subversion repository
maintained at http://dev.saxonica.com/archive/opensource. The Subversion repository on the SourceForge
site is no longer maintained.

The following bugs are cleared in 9.5.1.10 & 9.5.1.9, issued 2015-04-14 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

    2353    NPE in schema-aware transformation
    2344    Expression 'position() eq last()' wrongly evaluated inside an xsl:result-document instruction
	2341	saxon:stream() fails to abort parsing when all data processed
	2338	saxon:compile-stylesheet() modifies Configuration's ErrorListener
	2322	In a format-number() picture, colon (':') is misinterpreted as a digit
	2318	Function name "lt" not allowed if annotations are present
	2298	Buggy behavior triggered by binding extensionElement in Saxon-EE 9.5
	2291 	byte-code error java.lang.NoSuchMethodException: net.sf.saxon.om.SequenceIterator.itemAt(int)
	2275    Controller.inUse is never set to true
	2274	Links to command line documentation
	2248	Can no longer pass null value to declareGlobalVariable
	2238    Configuration.unravel() tests for "same Configuration" not "compatible Configuration"
	2232	Invalid XQuery variable reference throws NPE, or evaluates without error message
	2230    Large number of class loaders created in byte code
	2217    JAXP: SchemaFactory.newSchema() supplying an Element rather than a Document
	2210	Concurrent Schema Import
	2209    Namespace Fixup doesn't work for default namespace when input is TinyTree and result is TinyBuilder ...
	2207	9.5 html documentation - Change History and Function Library not working
	2187	Entity Re-Declarations Bug
	2186    Documentation: XQuery Update conformance section
	2152	Saxon-EE NullPointerException in ValidatorImpl
	2120	NullPointerException if there's no license key
	2116    Out-of-date documentation for ExtensionFunctionDefinition
	2097    Error in documentation of fn:unparsed-text-lines()
	2036	Documentation: functions are not in alphabetical order
	1773	StandardCollectionURIResolver doesn't allow streaming



The following bugs are cleared in 9.5.1.8, issued 2014-10-31 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

	2097 Error in documentation of fn:unparsed-text-lines()
	2103 Memory usage is very high running a transformation
	2123 In-scope namespaces for virtual copy
	2127 Rounding double values
	2129 Bytecode generation failure with "for allowing empty" & positional variable: assertion error
	2133 Concurrent Bytecode Generation in Saxon-EE crashes
	2134 Incorrect bytecode generation for xsl:choose with no otherwise
	2130 XPath referencing attribute with namespace fails when using DOM (Partial fix applied)
	2144 Error not caught in xsl:try catch block in bytecode
	2147 NullPointerException thrown in bytecode (gen_SlashContextMappingFunction)
	2148 Casting with pattern facet and canonical lexical representation
	2149 Cannot compile date:AOtoISO: CardinalityChecker: compileToItem called when multiple items allowed
	2150 java.lang.IllegalArgumentException thrown in DoubleToStringCompiler
	2153 Exception using parse-xml-fragment function with linked tree model
	2179 err: variables undeclared within an AVT
	2181 Try/catch within a loop gives wrong output
	2183 Bytecode generation: xs:string returns "" instead of ()
	2184 With a DOM with unknown baseURI, unparsed-entity-uri() throws a NullPointerException
	2199 NullPointerException thrown in DotNetDomBuilder
	2200 Incorrect type inference for floor() function
	2204 Nested multithreaded xsl:for-each

The following bugs are cleared in 9.5.1.7, issued 2014-08-06 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

	2104 ArrayIndexOutOfBounds in Chain.itemAt()
	2105 NullPointerException getting string value of DOM Document node
	2107 Byte code CannotCompileException for DoubleToInteger conversion
	2109 index-of (bytecode compilation?)
	2117 Byte code generation goes for boolean value instead of numeric
	2118 .NET SchemaValidator.ErrorList missing information
	2119 NullPointerException when running Saxon-EE in unlicensed mode



The following bugs are cleared in 9.5.1.6, issued 2014-07-10 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

	2093 Type-checking an arithmetic expression takes quadratic time
	2036 Documentation: functions are not in alphabetical order
	2040 Execution time wrongly formatted with -t output
	2043 Empty maps not passing type checking inside compound <xsl:map> statements
	2044 "Getting started" example in documentation doesn't work on all shells
	2049 Method "net.sf.saxon.tree.linked.ElementImpl.getPrefixForURI(String)" returns URI instead of prefix
	2052 Multithreading bug with xsl:for-each saxon:threads=N
	2056 Unable to download saxon-he 9.5 with maven
	2059 NullPointerException while streaming if optimization is off
	2062 XsltTransformer.setSchemaValidationMode() has no effect
	2063 Arithmetic expression fails with ClassCastException if inferred static type is a union type
	2064 Poor diagnostics when license file expired
	2067 NullPointerException while streaming with multiple local variables
	2068 For HTML5 serialization, "5.0" is recognized but "5" is not
	2069 resolve-uri() still does not support "jar:http:" URIs
	2070 Internal Saxon error: local variable encountered whose binding has been deleted with xsl:sort @order
	2071 xsl:number ignores grouping when the value is > 2^64
	2077 Performance: $x[$x[$i]] with bytecode enabled
	2081 Line endings are not normalized in library modules
	2084 Failed to execute an XSLT 3.0 stylesheet that uses the 'parse-xml-fragment' function
	2085 Exception java.lang.AssertionError: Internal error: invalid slot number for local variable (0)
	2092 Multiple Definitions for the Same Key performs badly if the key contains duplicates
	2100 Incorrect behaviour when an abstract type is used for validation
	2102 Saxon should support an empty DOMSource(). As-is, NPE in net.sf.saxon.dom.DOMObjectModel.unravel.
	1974 Performance regression with tail expressions (A reopened bug which has been fixed)

Other fixes that were made in this release (updated 2014-10-31):
	2041 NPE with unknown cause
	2058 No location information for xsl:message if evaluation of error-code fails


The following bugs are cleared in 9.5.1.5, issued 2014-03-25 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. Whilst Saxon 9.5.1.5 is a maintenance release, in the Saxon-HE edition 
we have moved support for XQJ from the main JAR file, because of concerns about whether the license was truly open source, 
but for the code to remain available as a separate JAR file, i.e. 'saxon-xqj.jar' :


    2038	Collations in XQuery group-by
    2037    EXPath file:path-to-native and file:exits() on Mac OS 10.9
	2035	Incorrect static type inferred for (A castable as UnionType)
	2032	Spurious type-checking error XPTY0020
	2031	NullPointerException after optimizing saxon:stream()
	2030	NullPointerException while streaming
	2029	tail(data()) - function should have been resolved at compile time
	2028	Streaming string-join#1 causes ArrayIndexOutOfBoundsException
	2026	When streaming, distinct-values() fails with NullPointerException if collation is not known statically
	2025	snapshot() fails with NullPointerException if argument is an empty sequence
	2024	NullPointerException testing streamability of "/"
	2022	Copying xsl:stream instruction gives ArrayIndexOutOfBoundsException
	2021	Various odd issues --- crashing when maps called with empty arguments
	2020	Line number failing to show in error message
	2019	NullPointerException when xsl:stylesheet element appears not as outermost element
	2016	Premature exit from XQuery streaming
	2015	doc() called while multithreading; unsafe access to document pool
	2013	saxon:stream() in XQuery not streaming when it should
	2011	xsl:number/@count pattern with predicates: failure to allocate stack frame slot
	2008	Problem using xsl:copy-of with an xsl:variable
	2007	XQJ support in 9.5.1.4 moved into a separate jar file.
	2004	Missing select on xsl:iterate/xsl:param
	2003	@composite = "yes" : current-grouping-key() returns a single string
	2002	XPathException was unhandled in .NET
	2001	saxon:discard-document does not work with accumulators
	2000	Failure with streaming of xsl:iterate
	1999	Documentation of saxon:evaluate
	1998	Spurious warning about optional field in xs:key
	1997	for-each loops through empty collection
	1994	W3C spec change for xsl:iterate
	1993	Poor error message for file open failure on packaged stylesheet file
	1992	Template pattern incorrectly identified as never matching
	1988	Incorrect namespace in several test cases in the QT3 test suite
	1985	Warning SXXP0005 may not be relevant
	1984	Configuration file examples in documentation say version="1.1"/"2.1"
	1978	Javadoc for FeatureKeys is incomplete
	1970	In the .NET API documentation, new XdmAtomicValue(String) is absent
	1955	Poor DOMSender performance with Xerces DOM
	1946	Commandline documentation for XQuery has missing link.
	1944	Illegal configuration-file syntax in META-INF/services/javax.xml.xpath.XPathFactory



The following bugs are cleared in 9.5.1.4, issued 2014-01-22 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :


	1468: saxon:import-query and global variables
	1473: java.lang.AssertionError: Value of variable is undefined (null). Variable reference $saxon:current24880015
	1474: XQuery switch statement fails with NPE if evaluated statically
	1517: java.lang.NullPointerException for "cast as" in AVT
	1555: Serialization parameter suppress-indentation not working
	1671: format-number() (XSLT 2) in the Saxon documentation
	1785: alphanumeric sort => should use longint
	1895: Documentation: -strip on command line
	1926: Bad type checking for attribute(x, xs:untyped)
	1927: Spurious error optimising void filter expression
	1928: Singleton value not recognized as numeric subscript
	1929: unsorted() optimization is too aggressive
	1930: xsl:stream focus dependency
	1931: avg() over empty sequence fails under bytecode generation
	1932: NullPointerException using -explain with xsl:merge
	1933: NullPointerException when current() used in a pattern predicate
	1938: ClassCastException in SimpleStepExpression
	1942: Function current should have been resolved at compile time
	1947: EXPath file:write() and file:append() fail to close file
	1948: Documentation: signature of saxon:adjust-to-civil-time is wrong
	1951: xsl:analyze-string - no error if child elements in wrong order
	1957: Incorrect default priority for patterns with predicates
	1958: saxon9-unpack.jar is empty
	1964: Failure to load PE configuration file via JAXP API
	1965: Documentation: spurious "top" in lists of JAR files
	1966: ClassNotFoundException: net.sf.saxon.lib.StAXHandler
	1967: Command line: use of "-" as positional argument
	1969: Incorrect SVN URL in maven pom file
	1971: Burst-mode streaming not working as documented
	1973: HTML5 serialization: default attributes
	1974: Performance regression with tail expressions
	1977: Schema processor does not reject xs:group/xs:sequence/@maxOccurs
	1979: format-number() applied to negative zero
	1980: Serialization property item-separator not implemented
	1981: GROUP BY for a collection of map fails unless wrapped in a try-catch
	1982: Command line: colon in parameter values
	1986: System.ArgumentException: Type name was too long. The fully qualified type name must be less than 1,024 characters
	1987: Bytecode generation verification error: Method owner: expected Ljava/lang/String;, but found Ljava/lang/CharSequence;


The following bugs are cleared in 9.5.1.3, issued 2013-10-25 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

    1897: Saxon-HE binary jar not properly compressed (only under maven)
	1810: SXST0063: Template body is an expression that returns nodes from the streamed input document
	1854: Source code cannot easily be browsed
	1866: Parse errors in imported stylesheet cause no exception
	1877: current() throws dynamic error in expand-text directives
	1878: bind-group attribute not working properly in for-each-group
	1882: net.sf.saxon.s9api.SaxonApiException: net.sf.saxon.trans.XPathException: Axis step child::element while validating document
	1885: AttributeCollectionImpl.setAttribute()
	1886: In XML Schema 1.0 maxOccurs="unbounded" on a particle of the "all" compositor should be reported as an error
	1890: Problems with accumulators
	1891: NullPointerException with XSD 1.1 conditional type assignment
	1893: java.lang.NullPointerException because of xsl:strip-space
	1894: IndexOutOfRangeException thrown in .NET
	1899: Parameter not evaluated when the only usage is in a predicate of a pattern
	1901: PrependIterator.getAnother()
	1907: Use of expanded QName in XQuery computed attribute constructor
	1908: Performance: patterns calling a function in a predicate
	1910: Infinite recursion in Optimizer
	1912: Race condition on loading license file
	1916: Internal Saxon error: local variable encountered whose binding has been deleted (intersect operator)
	1917: Namespace undeclarations in XQuery element constructors
	1918: Incorrect W3C streamability analysis for filter expressions
	1919: Failure to detect that query parameters are in wrong Configuration
	1920: NullPointerException while evaluating global variable
	1924: ArrayIndexOutOfBounds in Chain.ChainIterator
	1925: java.lang.UnsupportedOperationException with message append() method is not supported in this class


The following bugs are cleared in 9.5.1.2, issued 2013-08-29 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

	1873	base64Binary output method writes to wrong file
	1872	doc-available() fails with error on XML parse error
	1868	Ineffective optimization of GeneralComparison
	1866	Parse errors in imported stylesheet cause no exception
	1864	Subclassing StaticQueryContext
	1862	Saxon Documentation - fn:serialize() - non-working link
	1861	Error location with generated bytecode
	1858	Missing link in documentation
	1857	Result-document left open after dynamic error
	1854	Source code cannot easily be browsed
	1853	"jar" URIs no longer supported in 9.5
	1852	ArrayIndexOutOfBounds doing Unicode normalization
	1851	Fallback to HE when there is no license
	1848	ClassCastException when pattern on streamable template is not a NodeTest
	1847	NullPointerException when assessing the streamability of an attribute-set
	1846	Sample C# applications omitted from saxon-resources
	1844	Out-of-memory due to non-synchronisation of TinyTree statistics
	1842	Greek perispomeni and normalize-unicode
	1840	Reflexive extensions function arguments not casting correctly
	1838	XQuery parsing bug: incorrect function declaration syntax is accepted
	1836	Constants with different names and the same value
	1835	Namespace inheritance in XQuery
	1834	ClassCastException in XdmNode.getParent()
	1831	java.lang.ArrayIndexOutOfBoundsException when XML is processed with XSL
	1830	Multithreaded DOM Access
	1829	Undeclared namespace in DOM input
	1828	Incorrect optimization of /a/b/c[2]/d[@e='pqrs']
	1824	Saxon-EE collection() fails if collection is empty
	1823	NullPointerException using DOM tree with parentless element
	1822	Incorrect Javadoc details in method call of class ExtensionFunctionCall
	1820	Documentation browser: accept %21 in URL fragment
	1819	java.lang.UnsupportedOperationException: Cannot enumerate an infinite set exception
	1813	Absent XHTML DTD entities
	1810	SXST0063: Template body is an expression that returns nodes from the streamed input document


The Saxon 9.5.1.1, is primarily a maintenance release. However, the increment in the third part of the version number indicates that there are
also some small functionality changes. The details of these changes can be found at:

http://www.saxonica.com/documentation/index.html#!changes/installation/9.5-9.5.1.1

The following bugs are cleared in 9.5.1.1, issued 2013-06-19 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

	1817	Element output with incorrect prefix (bytecode only)
	1812	Legal pattern rejected
	1811	Local variable used in a pattern
	1809	XSLT 3.0 on-no-match="deep-skip"
	1807	HTML 5 serialization: DOCTYPE declaration
	1806	HTML 4.0 serializer, end tags for XHTML elements
	1805	require/prohibit feature names
	1802	Hyphens in regular expressions
	1801	Cast to union fails with bytecode generation
	1800	format-dateTime - Ignored padding given the picture with width for roman numerals
	1799	Handling of calendar argument of format-date()
	1798	Incorrect example of ExtensionFunctionCall
	1795	Increased memory requirements of tree model in Saxon 9.4 compared to Saxon 9.3
	1793	Problem with EntityResolver and document()
	1792	ArrayIndexOutOfBoundsException when converting xs:string variable with occurrence indicator
	1790	[Regression?] Saxon-HE 9.5 and XsltExecutable.getGlobalParameters()
	1789	Transformation fails when DOMSource has expanded EntityRef in it
	1788	Serialization problem with XHTML meta tag
	1787	Performance of substring()
	1774	xsl:stream not documented
	1772	Saxon release userdoc incomplete
	1767	CDATA Section not being serialized to HTML when using option cdata-section-elements
	1759	Unsupported node type in DOM! 10 instance
	1752	Scaleability of Chain sequence



The following bugs are cleared in 9.5.0.2, issued 2013-05-22 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

	1783	Unknown system function function()
	1782    Empty unions in XSD 1.1
	1780	version decl for XQuery incorrectly relaxed under XQuery 1.0
	1779	Reserved function name function not handled correctly
	1778	Handling errors in processing xsi:schemaLocation
	1777	Java.lang.ClassCastException: net.sf.saxon.value.Int64Value cannot be cast to net.sf.saxon.om.FunctionItem
	1776	DTD module xhtml-inlpres1.mod is miscatalogued
	1775	format-number() requires '0' in picture, disallows '9'
	1771	TypeCheck bypassed by optimizer
	1768	search tool broken in Saxon documentation
	1766	Incorrect serialization of HTML 5.0 elements in XHTML ns
	1765	<embed> missing from list of HTML 4.0 tags that have no closing tag
	1762	Inefficient hashing for applyTemplates
	1761	Bad link to documentation from command-line help
	1760	Regular expression matching zero-length string
	1758	count() is interpreted, not compiled
	1757	function-available() on constructors for abstract types
	1756	Saxon HE 9.5 .Net sample project fails to build with Target Framework set to 3.5
	1755	format-date() with [w] option (week in month)
	1754	Redistributing Saxon-HE .NET with 3rd party notice files
	1753	EXSLT extension function NPE when passed empty sequence
	1752	Scaleability of Chain sequence
	1751	Wrong location information when debugging
	1750	Lazy evaluation of variables: regression in 9.5
	1749	Error message for saxon:index() incorrect
	1748	saxon:index available in Saxon-PE
	1747	s9api piping XQuery output into XSLT destination
	1746	ProgressiveIterator.materialize()
	1745	High	Variable stack frame allocation issue - PE 0.5.0.1
	1744	NPE in compiling xsl:iterate under
	1743	Broken links in documentation
	1742	Reflexive extension functions: passing empty sequence
	1741	Out of date information on extensibility
	1740	Performance regression for $x[$i]
	1738	Null pointer exception when bytecode is on
	1737	collections with recurse=yes
	1736	Out of date info in documentation about EQName
	1735	IndexOutofBounds exception using substring() with non-BMP string
	1734	xs:error not supported in XPath/XSLT/XQuery
	1733	.net api documentation: interface members not shown
	1652	fn:collection() does not declare its results to be in document order


The first release in this series, 9.5.0.1, was issued on 16 April 2013. 

Bugs can be reported, and known bugs inspected, on the Saxon community site at https://saxonica.plan.io/projects/saxon
The sourceforge bug tracker is no longer maintained.