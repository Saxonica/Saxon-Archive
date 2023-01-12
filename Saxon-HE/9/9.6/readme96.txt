==============================

Saxon-HE 9.6 is the latest major release of the open-source edition of Saxon. 
It is available for the Java platform (.NET platform coming shortly).

The current maintenance release is Saxon-HE 9.6.0.10.

The documentation for Saxon is at http://www.saxonica.com/documentation/
and includes a detailed list of changes for each release.

For the Java platform, download file SaxonHE9-9-0-10J.zip. Installation instructions are at:

http://www.saxonica.com/documentation/index.html#!about/installationjava

The file saxon-resources9-6.zip contains documentation, sample files, test drivers and other miscellaneous resources. 
It is common to both platforms, and is not normally updated when new maintenance releases appear.

The file saxon9-6-0-10source.zip contains source code for both platforms; a new version is produced with each
maintenance release. Source code with the latest patches can also be obtained from a Subversion repository
maintained at https://dev.saxonica.com/repos/archive/opensource. The Subversion repository on the SourceForge site is no longer maintained.


The following bugs are cleared in 9.6.0.10, issued 2016-12-02 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues:


    2789 File overwritten with empty file by XQuery Update
    2795 Error message "Value of {cdata-section-elements} must be a list of QNames in '{uri}local' notation"
    2812 Incorrect type analysis of non-executed xsl:for-each-group body
    2824 StringIndexOutOfBoundsException: String index out of range: -3 exception thrown
    2868 Better report "PatternSyntaxException"
    2869 problem with streamable mode
    2883 Regression Error in Saxon 9.7.0.4: Internal Error Evaluating Template Rule
    2899 StaxToEventBridge Incorrectly Calling getText() for PI data
    2901 StaxToEventBridge fails to retain unused namespace declarations
    2914 Concurrency Issue: Internal error evaluating template
    2926 Memoization of last remembered number is not thread-safe
    3049 saxon:current-mode-name() returns non-empty
    3052 Performance issue - differences between HE/PE/EE especially on .NET


The following bugs are cleared in 9.6.0.9, issued 2016-05-26 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues:

    2420 EXPath File update to version 1.0
    2490 ColumnNumber property in StaticError incorrectly spelt
    2532 Query Initializer hook invoked too late to set ModuleURIResolver
    2536 Failure to check that node returned by extension function has wrong NamePool
    2539 -t option should report when streamed processing is happening
    2540 Unwanted warning with JAXBSource
    2545 Invalid slot number: local variables in match pattern with mode="#all"
    2548 Property name typo in class StandardLogger
    2552 AssertionError during byte code generation
    2559 Dynamic value of xsl:result-document/@format is ignored
    2560 xsl:fallback is not allowed as a child of xsl:merge
    2561 java.lang.NullPointerException with nested xsl:iterate
    2567 java.lang.NullPointerException with external variable in xsl:iterate/on-completion
    2570 Wrong exit code on error (XQuery command line)
    2571 XQuery group-by leads to "Local variable $x has not been allocated a stack frame slot"
    2572 StringIndexOutOfBounds in formatDate() with large width modifier
    2577 Performance regression in 9.6 caused by complex union patterns
    2578 lang() only considers first hyphen
    2590 NPE when saxon:assign refers to an undeclared variable
    2602 Incorrect TimingTraceListener class in -T: command line documentation
    2614 Download link for saxon-resources9-7.zip is missing
    2622 Combining use-character-maps and normalization-form="NFC" attributes produce unwanted output
    2651 select="xs:string(xs:dateTime('9999-12-31T23:59:59.9999999'))" gives => '9999-12-31T23:59:59.:"
    2666 JAXP Validator.validate() throws an exception if there are validation errors
    2667 format-date() week-in-month numbering is incorrect
    2688 xsl:analyze-string gives wrong results with bytecode enabled
    2702 XSL: castable as xs:base64Binary crashes if false()
    2714 Streamed grouping using xsl:for-each-group group-starting-with and snapshot(current-group())/.. gives different result than unstreamed grouping
    2728 Failed to load org.ccil.cowan.tagsoup.Parser
    2735 ArrayIndexOutOfBoundsException while evaluating regular expression
    2745 org.apache.xerces.jaxp.SAXParserFactoryImpl not found in .NET
    2754 Memory leak of an instance model from a schema containing QName valued elements

The following bugs are cleared in 9.6.0.8, issued 2015-12-10 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues:


    2301 Confusion between IDREF and NILLED properties in TinyTree
    2314 Stylesheet Base Uri with spaces causes issues when compiling stylesheet [Saxon.HE 9.6N]
    2413 Internal problem: Base value for indexed lookup is not indexable
    2418 HTML documentation: magnifying glass is present but dormant
    2441 Ordinal numbering schemes in ICU
    2447 Internal error "invalid replacement" in saxon:assign
    2448 No error for xsl:function/xsl:param[@required='no']
    2450 Unexpected result using w3c accumulator sample
    2451 Exceptions from Saxon-EE optimization
    2454 match="//elname" with mode typed="strict"
    2456 "compileLibrary" fails for file with private variable
    2460 Saxon release repository and tagging
    2461 Xslt30Transformer: getting raw template results
    2465 XQuery Update: moving an attribute
    2466 NoSuchMethodException during bytecode generation: CodepointCollator.compareCS
    2467 FeatureKeys.ALLOW_OLD_JAVA_URI_FORMAT value is inverted
    2470 Prefixed function name in attribute of XQuery direct element constructor
    2472 Opensource code on sourceforge should be after preprocessing
    2478 accumulator-after gives wrong state
    2480 parse-json(...\u...)
    2482 Attributes of child element of root element are copied into root element when serializing with indentation.
    2484 xml-to-json() has a dummy implementation that outputs "a string"
    2486 Using -catalog with .NET command line
    2487 Incorrect value returned by match-substring/regex-group()
    2488 XInclude with Saxon 9.6 in .NET application not working
    2489 Performance for pattern with first position predicate
    2491 NPE in class Whitespace
    2492 ClassCastException in StringValue class when calling xquery function fn:string-length()
    2493 FastStringBuffer.getCharArray()
    2495 Named xsl:output inheriting from imported nameless xsl:output
    2497 function-lookup should not fail if built-in function not found
    2501 NPE supplying parentless element to XPathSelector.setContextItem
    2513 Spurious message "Saxon is not able to process Microsoft's WD-xsl dialect"
    2518 Regex: back references matching empty captures
    2519 Third parties jars outdated
    2524 AssertionError due to class loading order
    2527 Failure calling a function returned from a template
    2532 Query Initializer hook invoked too late to set ModuleURIResolver

The following bugs are cleared in 9.6.0.7, issued 2015-08-05 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues:

     2359 dynamic calls to fn:analyze-string()
     2378 NullPointerException using saxon:next-in-chain via JAXP interfaces
     2382 Unclosed Emitter writter
     2389 Streaming failure: No transmission filter available for let $zz:zz472117691 := ...
     2392 java.lang.RuntimeException: Cannot instantiate a Configuration
     2393 Configuration file example in the documentation contains errors
     2394 Saxon .NET uninstaller doesn't remove assembly from GAC
     2395 Saxon .NET still has references to .NET framework 2.0
     2396 Code contains non-working implementation of multi-threaded apply-templates
     2397 document-uri() returns bad URL on Windows but Not Mac
     2399 Spurious warning when required type is empty-sequence()
     2400 Warning messages for invalid properties in configuration file
     2401 Performance regression for positional patterns
     2403 IDREF validation failures not detected by xsl:copy-of
     2404 System.NullReferenceException: Object reference not set to an instance of an object
     2407 DOM wrapper: NPE accessing an empty text node
     2410 Add ErrorObject on DynamicError
     2411 Java8 - SchemaFactoryConfigurationError: Provider for class javax.xml.validation.SchemaFactory cannot be created
     2412 NPE evaluating pattern containing global variable in streaming mode
     2414 org.xml.sax.SAXNotRecognizedException: http://javax.xml.XMLConstants/feature/secure-processing
     2415 Error found in Issue #2160 appearing in Saxon-HE-9.6.0-5
     2416 NPE with expand-text and empty text element
     2417 Failure if a type contains both an enumeration and a restriction
     2427 In receiver pipeline, filters may be skipped
     2428 NumberFormatException comparing zero-length-string to a number
     2433 Multi-threaded xsl:for-each
     2435 Equality fails due to type comparison
     2436 Multithreading bug in format-date()
     2438 XQuery group-by does not handle implicit timezone correctly



The following bugs are cleared in 9.6.0.6, issued 2015-06-05 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues:

    2111 setConfigurationProperty prevents propagation of ModuleURIResolver
    2225 Optimization of filter expressions in 1.0 mode
    2306 InvalidCastException: Unable to cast object of type org.apache.xml.resolver.tools.CatalogResolver
    2308 NullPointerException using xsl:choose when streaming
    2312 Optimizations stop disable-output-escaping working
    2338 saxon:compile-stylesheet() modifies Configuration's ErrorListener
    2341 saxon:stream() fails to abort parsing when all data processed
    2343 IncompatibleClassChangeError
    2344 Expression 'position() eq last()' wrongly evaluated inside an xsl:result-document instruction
    2345 Transformation failed: Error opening packaged stylesheet file or Invalid URI for stylesheet
    2351 Validating an XSD from command line gives a stacktrace
    2353 NPE in schema-aware transformation
    2355 cs samples omitted from Saxon-resources zip file
    2356 XPathExpressionImpl always logs to System.err
    2357 StreamWriterToReceiver.startElement(localName)
    2360 java.lang.RuntimeException was unhandled by user code
    2361 fn:format-number - escapes not accepted in decimal format declaration
    2363 License (serial number null) has expired
    2364 Cannot transform an XSLT stylesheet when the xsl:output contains unknown attributes
    2367 Performance regression with xsl:key
    2368 DOM4J wrapper.copy() has O(n^2) performance
    2375 Spurious warnings from xs:override
    2376 DOM lack of thread-safety
    2377 Private classes/methods in LinkedTree
    2378 NullPointerException using saxon:next-in-chain via JAXP interfaces
    2386 Validation errors missing column number
    2387 NPE when applying an XSLT transformation with schema based validation feature enabled
    2388 <xs:choice/> accepts empty content as valid
    2390 Wrong result from replace()
    2391 Decimal formats should disallow (say) decimal-separator=6


The following bugs are cleared in 9.6.0.5, issued 2015-03-27 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

	2230    Large number of class loaders created in byte code
	2287    Incorrect error message in testdriver
	2289    NPE in ContextItemTypeExpression
	2290    Incorrect current-grouping-key() with streamed group-adjacent
	2291    byte-code error java.lang.NoSuchMethodException: net.sf.saxon.om.SequenceIterator.itemAt(int)
	2292    Navigation using child axis is not supported from a streamed input node
	2296     Serializer.SetOutputWriter seems to ignore omit-xml-declaration setting [Saxon-HE 9.6.0.4N]
	2297     Multiple comparisons in expressions wrongly allowed in XQuery syntax
	2298     Buggy behavior triggered by binding extensionElement in Saxon-EE 9.5
	2299     Saxon-EE rejects recursive XQuery function, when there is no license file
	2300     Namespace context is lost when inlining an expression containing call to accumulator-before()
	2302     Node identity: collection() ↔ doc()
	2303     Saxon allows xsl:stylesheet/@default-validation="strict"
	2304     Streaming: early exit not working
	2305     FactoryConfigurationError: Provider org.apache.xerces.jaxp.SAXParserFactoryImpl not found
	2306     InvalidCastException: Unable to cast object of type org.apache.xml.resolver.tools.CatalogResolver
	2307     Optimization disabled in 1.0 compatibility mode
	2309     NullPointerException with dynamic call on fn:head()
	2310     saxon:next-in-chain extension to xsl:output buggy when xsl:result-document is used
	2311     Attributes starting with an underscore (_) are removed
	2312     Optimizations stop disable-output-escaping working
	2313     index-of() -- iterator.getAnother() gives incorrect results
	2315     NullPointerException in generated bytecode
	2316     xsl:validation="strict" fails when element uses type alternatives
	2318     Function name "lt" not allowed if annotations are present
	2319     -TP output ignores time spent evaluating global variables
	2320     "invalid slot number for local variable" error when streaming
	2322     In a format-number() picture, colon (':') is misinterpreted as a digit
	2323     Different XSLT compilation error obtained when I set SAXResult to transformer
	2324     Focus-dependent attribute sets
	2327     Deadlock for concurrent instantiation of Configuration and EnterpriseConfiguration
	2328     Reflexive extension functions using java.util.List
	2329     Configuration file schema config.xsd (in samples) needs updating
	2330     Spurious validation error if an IDREF element is nilled
	2331     dref() applied to a list containing both IDREF and non-IDREF values
	2332     Saxon Configuration: Schema


The following bugs are cleared in 9.6.0.4, issued 2015-01-14 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :


	2246	The doc file should be named saxon9he-api.xml, otherwise Visual Studio ignores it.
	2210	Concurrent Schema Import
	2219	xsl:next-match; patterns using match="$var" syntax
	2247	Whitespace normalization in union types
	2248	Can no longer pass null value to declareGlobalVariable
	2249	StylesheetPackager missing in SaxonEE9-6-0-3N-setup.exe?
	2250	The output file cannot be deleted after executing an XSLT transformation
	2251	NullReferenceException when transforming to TextWriterDestination [Saxon-HE 9.6.0.3]
	2253	Saxon HE 9.6.0.2 with -xmlversion:1.1 reports Unrecognized version 1.1: treated as 1.0
	2255	xsl:assert no longer producing message in Saxon-PE 9.6.0.3J
	2257	XSLT3.0 support on xsl:* elements
	2258	QName.ToString() returns incorrect lexical form
	2260	Saxon.Api documentation: missing class descriptions
	2261	With bytecode on, apply-imports fails to set current component
	2271	AIOOBE with large xml file
	2272	XdmNode.BaseUri throws exception when NodeInfo.getBaseURI() returns null
	2273	collection() does not use built-in copies of W3C DTDs
	2274	Links to command line documentation
	2275	Controller.inUse is never set to true
	2277	match="x/descendant::y[1]" gives spurious matches
	2278	Pattern descendant::text()[1] gives a spurious warning, and no matches
	2279	Redistributing Saxon-HE .NET with 3rd party notice files
	2282	IdentityTransformer with empty DOMSource
	2283	s9api s9api transformation pipeline not working under .NET
	2286    saxon9-icu jar missing from Saxon-EE 9.6.0.3 release


The following bugs are cleared in 9.6.0.3, issued 2014-12-02 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :


	2238	Configuration.unravel() tests for "same Configuration" not "compatible Configuration"
	2232	Invalid XQuery variable reference throws NPE, or evaluates without error message
	2230	Large number of class loaders created in byte code
	2187	Entity Re-Declarations Bug
	2152	Support	Saxon-EE NullPointerException in ValidatorImpl
	1935	.NET API documentation file
	2225 	Optimization of filter expressions in 1.0 mode
	2226 	NullPointerException in UserFunction.isInlineable()
	2227 	NullPointerException when reporting type error in accumulator
	2228 	Invalid slot number when xsl:accumulator/@initial-value uses local variables
	2229 	Accumulators failing to recover from out-of-memory conditions
	2233 	Poor diagnostics on type error with higher-order function
	2234 	9.6 optimizations break relative XPath with predicates
	2235 	@expand-text ignored because XSLT 3.0 not enabled
	2236 	Parameters set using Transformer.setParameter() not accessible using getParameter()
	2240 	JAXP-XPath page in the documentation need updating
	2242 	JAXP SchemaFactory API: ErrorHandler is not notified of schema errors
	2243 	NullPointerException in MessageEmitter.endDocument()
	2244 	No location information available when xsl:import fails
	2245 	Base URI not preserved after deleting xml:base attribute




The following bugs are cleared in 9.6.0.2, issued 2014-11-13 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :



	2218	ByteCode generation failure during compilation in 9.6
	2217	JAXP: SchemaFactory.newSchema() supplying an Element rather than a Document
	2216	SystemId information not available to TraceListener
	2215	ErrorListener registered with the JAXP TransformerFactory is ignored
	2214	With JAXP transform() method, result.getSystemId() should act as base output URI
	2213    Comparing QName to untypedAtomic crashes
	2212	function-available('exslt:node-set') returns false
	2211	strip-type-annotations not working with XSLT30 applyTemplate
	2209	Namespace Fixup doesn't work for default namespace when input is TinyTree…
	2208	xsl:character-map failure in s9api interface when source is a Xdm node
	2206	User documentation incorrectly states default XQuery version is 1.0
	2204	Nested multithreaded xsl:for-each
	2202	ExternalObjectType for Java and .NET
	2201	Setting ErrorListener on XQueryCompiler has no effect
	2200	Incorrect type inference for floor() function
	2195	NullPointerException in com.saxonica.pull.TreeWalker
	2194	No location information in output pipeline for SAXResult
	2191	Debugger access to global variables
	2190	NPE using xsl:use-package
	2189	Failure to stream output
	2188	Streaming xsl:merge logs "building tree" messages (with -t option)
	2186	Documentation: XQuery Update conformance section
	2184	With a DOM with unknown baseURI, unparsed-entity-uri() throws a NullPointerException
	2183	Bytecode generation: xs:string returns "" instead of ()
	2182	java.lang.RuntimeException: Method code too large thrown in query
	2181	Try/catch within a loop gives wrong output
	2179	err: variables undeclared within an AVT
	2178	NullPointerException in TransformerImpl.setParameter()
	2177	NullPointerException with literal FilterExpression
	2173	NullPointerException after inlining variables
	2172	xsl:apply-templates streaming: fails when processing grounded node
	2171	xsl:call-template is (unnecessarily) non-streamable
	2170	Passing down object reference to extension function not available
	2169	map{} is parsed as ExprSingle, not as a Primary
	2168	Setting parser features from the command line
	2167	NPE in PackageLibrary.getPackage()
	2166	Wrong result from fn:replace
	2165	Commandline -repeat:N not working properly
	2164	Empty DOMResult provided to transform method produces null result
	2163	saxon:next-in-chain is not working in Saxon 9.6
	2161	Attempt to use text value templates under Saxon-HE gives poor diagnostics
	2160	Attempting to set more local variables (3) than the stackframe can accommodate (1)
	2159	Current date and time can only be set once
	2158	Rejecting version="1.1" in xsl:stylesheet
	2199	NullPointerException thrown in DotNetDomBuilder
	2151	Dynamic type of the result of min()/max()



The first release in this series, 9.6.0.1, was issued on 2 October 2014. 

Bugs can be reported, and known bugs inspected, on the Saxon community site at https://saxonica.plan.io/projects/saxon
The sourceforge bug tracker is no longer maintained.