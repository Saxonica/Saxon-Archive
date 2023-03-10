==============================

Saxon-HE 9.9.1.8 is the latest maintenance release on the 9.9 branch of the open-source edition of Saxon.

A later branch, Saxon 10, has been available since March 2020 with new features, and is now considered stable.
See https://sourceforge.net/projects/saxon/files/Saxon-HE/10/ for details of maintenance releases on the Saxon 10 branch.

The 9.9 branch will remain supported until 2021-09-27, but in the interests of reliability, the maintenance
approach is conservative: bug fixes will only be produced if there is a strong technical reason, and minimal technical risk.

It is available for the Java and .NET platforms. Releases on C/C++/PHP platforms are still on 9.9.1.5, but will be updated soon.

The documentation for Saxon is at http://www.saxonica.com/documentation/
and includes a detailed list of changes for each release.

For the Java platform, download file SaxonHE9-9-1-8J.zip.

Installation instructions are at:

http://www.saxonica.com/documentation/index.html#!about/installationjava

The file saxon-resources9-9.zip contains documentation, sample files, test drivers and other miscellaneous resources. 
It is common to all platforms, and is not normally updated when new maintenance releases appear.

The file saxon9–9-1-8source.zip contains source code for both platforms; a new version is produced with each maintenance release.
Source code with the latest patches can also be obtained from a Subversion repository maintained at https://dev.saxonica.com/repos/archive/opensource.
The Subversion repository on the SourceForge site is no longer maintained.

The following bugs are cleared in 9.9.1.8, issued 2020-10-22 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

Bug #3202: --multipleSchemaImports has no effect when processing a cycle of schema documents
Bug #4238: In Saxon-EE, element-available() always returns true for IXSL extension elements
Bug #4323: ErrorListener for schema compilation invoked by xsl:import-schema
Bug #4347: Imported schema component model requires XSD version 1.1 when running XQuery with EE license
Bug #4391: Cannot find a 0-argument function named {http://saxonica.com/ns/interactiveXSLT}page()
Bug #4458: annotatedConfig.xsd does not allow saxon:attribute-order with *
Bug #4475: collection() fails java.util.concurrent.ExecutionException: java.lang.NegativeArraySizeException in 9.9.1.7
Bug #4476: Type error evaluating (fn:collection(...))
Bug #4478: java.lang.NullPointerException: while trying to invoke the method net.sf.saxon.om.Sequence.head() of a null object loaded from local variable 'actual'
Bug #4486: Attribute saxon:explain doesn't work
Bug #4490: NPE in getItemType if type hierarchy is null for merged maps.
Bug #4500: ArrayIndexOutOfBounds exception processing XDM Arrays in XSLT
Bug #4502: StackOverflowError on Saxon 10.0
Bug #4507: TinyTree used for assertion checking during schema validation includes excessive NamespaceBinding objects
Bug #4515: xsl:expose names="foo:*" with undeclared prefix foo causes NullPointerException
Bug #4518: Saxon XSD 1.1 using Saxon EE : use of xs:override
Bug #4519: Schema for SCM files does not allow @dmk attribute
Bug #4522: NullPointerException in Atomizer.iterate
Bug #4527: Regex with grouping and escape triggers java.lang.IndexOutOfBoundsException
Bug #4530: NullPointerException with `<xsl:copy-of select="/"/>`
Bug #4532: Compiling package to SEF fails when the package (a) uses keys, and (b) was itself loaded from a SEF file
Bug #4534: NullPointerException with invalidly-initialized global variable
Bug #4535: Misleading error message when array index out of bound
Bug #4541: Effect of xs:iterate/xsl:param/@as
Bug #4542: xsl:iterate/xsl:on-completion is not executed when processing a singleton
Bug #4543: Poor diagnostics when Transform -lib names a non-existent SEF file
Bug #4544: Packages listed in -lib on Transform command line must be source XSLT, not SEF files
Bug #4546: Bad location information when @use-when expression in an imported module has a syntax error
Bug #4548: Transform command line: spurious warning "Warning: -jit:on is ignored when -nogo is set"
Bug #4549: Saxon seems to use only a single index for multiple keys
Bug #4555: NullPointerException on Saxon 10.1
Bug #4563: Reuse of Xslt30Transformer causes wrong results (namespace)
Bug #4578: NullPointerException when array:fold-left|right $zero argument is an empty sequence
Bug #4582: format-date() with language="en-GB" prefixes the output with "[Language: en]"
Bug #4599: Supplying a character map in a serialization parameter document does not work when method is unspecified
Bug #4600: xsl:output with parameter document using method="adaptive" and character maps goes into infinite recursion
Bug #4602: Failure to locate parameter document: wrong base URI
Bug #4610: Bug in XPath optimizer with positional filter
Bug #4621: Exception raised by xsl:message terminate="yes" is intercepted by an Atomizer
Bug #4632: Stylesheet behavior varies depending on presence or absence of an xsl:message
Bug #4636: AssertionError compiling xsl:for-each-group with a higher-order-function
Bug #4640: Reference to a variable as an XPath step
Bug #4657: Ambiguous accumulator rules - should choose the last
Bug #4677: JUnit Tests testMultipleSchemaImportsOn and testMultipleSchemaImportsOff in TestValidator
Bug #4683: chained descendant axes gathering extra nodes
Bug #4684: NullPointerException compiling a stylesheet using eXist-DB transform() function
Bug #4688: EE 9.9.1.7 strange function parameter overriding
Bug #4689: IllegalStateException when getting XdmNode after chaining transformation
Bug #4691: Simplified stylesheet: xsl:version attribute is missing
Bug #4692: MapTest as subtype of Function Type
Bug #4698: Constructor XdmAtomicValue(decimal d) should use d.ToString(CultureInfo.InvariantCulture) instead of d.ToString()
Bug #4721: NullPointerException for calling fn:apply on empty sequence
Bug #4738: Optimization bug: xsl:choose with branches uniformly comparing untypedAtomic to numeric
Bug #4745: Testing for "the same" schema location is not sensitive to relative path
Bug #4765: NPE in LoopLifter (from StackOverflow)
Bug #4788: Exception thrown in ExtensionFunctionCall prevents thread pool shutdown
Bug #4793: xsl:copy-of with copy-namespaces="no" not working


The following bugs are cleared in 9.9.1.7, issued 2020-03-04 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

Bug #4246: XSLT variable contains document node with zero-length text node
Bug #4315: Named output ignored in 9.9 when using result-document with format attribute
Bug #4326: NullPointerException in XSLGeneralIncorporate
Bug #4331: XTSE3051 is not raised
Bug #4382: NullPointerException when running collection() with recurse=yes over a directory tree containing a large number of files
Bug #4403: Internal error when calling saxon:transform() with stylesheet without primary output
Bug #4405: Internal error: local variable encountered whose binding has been deleted
Bug #4406: README lists version 9.9.1.6 twice
Bug #4407: Unescaped right curly brace in regular expression
Bug #4408: Use of reserved namespace http://www.w3.org/2005/xpath-functions/map in user-defined function
Bug #4412: Disable-output-escaping has no effect when expand-text="yes" is in force
Bug #4414: Unnecessary log messages when using array:xxx() extension functions
Bug #4419: fn:normalize-unicode fails when DTD-based validation of source data is turned on
Bug #4430: Unpredictable output when streaming accumulators call other accumulators
Bug #4433: Saxon 9.9.1-5 outputs malformed XML due to duplicate default namespace declaration
Bug #4435: saxon:query() parameters
Bug #4437: IntHashSet.copy()
Bug #4441: Filter expression: NoDynamicContextException
Bug #4443: Type check: xs:byte, unary expression
Bug #4444: Problem with count(//parent::node()) and schematron comparison operators
Bug #4445: Problem with validation [ArrayIndexOutOfBoundsException in TinyTree]
Bug #4446: Schema-Aware Transformation: wrong node set
Bug #4447: Grouping with type declaration → XQST0094
Bug #4448: Local variables in xsl:key definition: Internal error: Cannot set local variable: no slot allocated
Bug #4449: NPE in CaseVariants
Bug #4453: SXST0067: No transmission watch for $input!element() with XSLT 3 code trying to use streaming
Bug #4457: MessageListener.message() terminate parameter set incorrectly
Bug #4459: ArrayIndexOutOfBoundsException at net.sf.saxon.serialize.HTMLIndenter.comment
Bug #4462: Incorrect code in XSDSimpleContentRestriction
Bug #4469: XQJ bindDocument() fails java.lang.IllegalStateException: Attempt to output end tag with no matching start tag
Bug #4470: Higher order functions under XQuery with EET license
Bug #4471: Base URI of configuration file supplied to fn:transform()
Bug #4473: URIResolver returning null when applied to source-location in fn:transform
Bug #4474: JDK9: Illegal reflective access by net.sf.saxon.java.JavaPlatform to constructor com.sun.org.apache.xerces.internal.jaxp.SAXParserFactoryImpl()



The following bugs are cleared in 9.9.1.6, issued 2019-12-06 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :


Bug #4279: net.sf.saxon.trans.LicenseException: Invalid license file found.
Bug #4314: Problem using current-merge-group() as argument to function call on the right hand side of simple map expression
Bug #4315: Named output ignored in 9.9 when using result-document with format attribute
Bug #4316: Reserved namespace "http://www.w3.org/2011/xquery-options"
Bug #4324: java.lang.NullPointerException when attribute xsl:use-package/@name is absent
Bug #4327: Error SXST0067: No transmission filter available for parent::(document-node()|element())
Bug #4328: saxon:get-pseudo-attribute() returns empty string on no match
Bug #4329: Getting warning "Source document ignored - query does not access the context item" although XQuery accesses /*/* (in right hand side of let expression)
Bug #4330: NullPointerException with XQuery using tumbling window in right hand side of let expression
Bug #4342: Sporadic spikes in XSL processing time due to internal looping
Bug #4343: XQMetaData.getXQJVersion() yields 0.9 rather than 1.0
Bug #4344: Incorrect type inference for schema-aware types
Bug #4346: Streamed optimization of xsl:copy doesn't converge
Bug #4350: TimingTraceListener (-TP option) has a built-in limit of 1500 on the number of stack frames
Bug #4353: Extra namespaces present when serializing XdmValue using Serializer API
Bug #4354: AttributeGetter does not have NO_NODES_NEWLY_CREATED property
Bug #4357: XSLT using accumulator passes streamability analysis but crashed with java.lang.UnsupportedOperationException: net.sf.saxon.trans.XPathException: Navigation using preceding-sibling axis is not supported from a streamed input node
Bug #4361: Multiple function bindings for EXPath Archive extract-map()
Bug #4363: ConcurrentModificationException in XQueryCompiler
Bug #4364: Better handling for UncheckedXPathException
Bug #4376: xsl:message content is not available within xsl:catch as $err:value
Bug #4378: analyze-string() in saxon:threads fails
Bug #4384: ClassCastException when accumulator declaration is in no namespace
Bug #4385: Infinite recursion in optimizer
Bug #4389: ClassCastException when running EE rather than HE
Bug #4390: Command line: -val has no default value
Bug #4394: NullPointerException during error recovery with a misplaced character map
Bug #4397: Obscure issue when using "instance of" inside function on results of array:filter
Bug #4399: functx:non-distinct-values says cannot compare xs:integer to xs:integer, in 9.8 EE only
Bug #4402: Cannot be cast to net.sf.saxon.type.ComplexType


The following bugs are cleared in 9.9.1.5, issued 2019-09-05 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

NOTE: Saxon.NET backward compatibility issue in regards to XdmEnumerator:
We hope this won't distrupt many users, but as a result of the patch to address the bug issue
https://saxonica.plan.io/issues/4296 the classes IXdmEnumerator and IXdmEnumerable disappear;
in their place we use IEnumerator<XdmItem> and IEnumerable<XdmItem>.
Any code that implements ExtensionFunctionCall will need to change; in most cases it's just a
matter of changing IXdmEnumerator to IEnumerator<XdmItem> in both the arguments and the result
type of the Call() method. The C# Examples in the saxon-resources have been updated to illustrates the changes.


Bug #3261: Duplicate binding slot assignment (switch optimization)
Bug #3711: SCM: inadequate representation of value constraints
Bug #4035: Exporting a stylesheet containing node-valued static variables
Bug #4048: NullPointerException when passing empty sequence as second argument to map:merge
Bug #4052: NullPointerException (no retained static context) during XSLT optimization in 9.8.0.15
Bug #4183: Cannot pass output parameters and document node parameters across the command line.
Bug #4227: java.lang.NullPointerException when using xsl:catch with @error on undefined errors
Bug #4229: The saxon:system-id() function does not return the correct systemID when the documents contains xi:include
Bug #4233: .NET Executables not code-signed
Bug #4237: Assertion error when bytecode generation fails
Bug #4245: NullPointerException during static type checking of call to map:merge
Bug #4246: XSLT variable contains document node with zero-length text node
Bug #4247: java.lang.ExceptionInInitializerError on Saxon 9.9.1.4 .Net where Java version works
Bug #4248: Setting a Parser Feature on command line in 9.9.1 HE
Bug #4250: fn:idref() does not match element nodes in linked tree
Bug #4251: java.lang.NullPointerException in Saxon-EE 9.9.1.4J but not Saxon-PE 9.9.1.4J
Bug #4252: XTDE3052 is not raised
Bug #4253: IKVM.NET throws java.lang.NoClassDefFoundError: 'com.sun.org.apache.xerces.internal.jaxp.SAXParserFactoryImpl'
Bug #4254: adjust-time-to-timezone(xs:time("18:25:29.900005Z"), ()) delivers "18:25:29."
Bug #4255: ItemTypeFactory.getItemType() assumes an item is either a node or an atomic value
Bug #4256: No easy way to convert s9api ItemType/SequenceType to the underlying representations
Bug #4257: Documentation javadoc search problems
Bug #4258: Checking for broken tag links in javadoc
Bug #4260: Does deferredValidationMode work?
Bug #4268: Documentation: xsl:number has out-of-date information on localisation
Bug #4270: Query doc('http://www.w3.org/2001/XMLSchema') fails "unknown protocol: classpath"
Bug #4272: In the HE source.zip file available on SourceForge, some data files are missing
Bug #4273: Performance problem in 9.9HE related to use of bulk copy
Bug #4275: Getting error Template rule is not streamable The merge-source/@select expression is not striding when using document-uri() of streamed primary input for merge-sources of xsl:merge
Bug #4276: Saxon-HE ignores xsl:function/@new-each-time="no", with a poor warning message
Bug #4278: Documentation: xsl:function/@cache
Bug #4279: net.sf.saxon.trans.LicenseException: Invalid license file found.
Bug #4280: Failure in file:base-dir(): "URI has an authority component"
Bug #4283: .NET API Documentation has two methods on XsltCompiler with the same signature Compile(Stream)
Bug #4289: file:exists() is always faise
Bug #4293: Streamability of accumulator-after in select expression of accumulator-rule with phase=end
Bug #4294: Using -x:org.ccil.cowan.tagsoup.Parser with .NET Transform.exe and Saxon 9.8 gives error XTSE0150: Namespace for stylesheet element should be http://www.w3.org/1999/XSL/Transform
Bug #4295: How to set Saxon licenseFileLocation in config file programmatically
Bug #4296: XdmEnumerator on .NET
Bug #4297: API Documentation of ExtensionFunction.Call() on .NET
Bug #4298: Uncaught "java.lang.UnsupportedOperationException: Cannot copy a variable reference whose binding is unknown"
Bug #4299: Saxon-HE v9.9.1.4 Exception XPDY0002 running .NET C# test example XsltSimple1.
Bug #4300: Getting warnings using XPathExecutable
Bug #4301: Incorrect namespace URI in error code produced using fn:error()
Bug #4303: On .NET, "Transform -?" reports class name as cli.Saxon.Cmd.DotNetTransform
Bug #4304: StandardEntityResolver: Turning off tracing messages
Bug #4305: java.lang.ClassCastException on .NET (in German Locale) when Transform.exe attempts to output memory usage
Bug #4307: .NET API Documentation: type hierarchy for XdmNode does not show XdmValue as an ancestor
Bug #4309: java.lang.ClassCastException: net.sf.saxon.tree.tiny.TinyTextualElement$TinyTextualElementText cannot be cast to net.sf.saxon.tree.tiny.TinyNodeImpl


The following bugs are cleared in 9.9.1.4, issued 2019-06-28 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :


Bug #2522: BaseURI from working directory?
Bug #4201: Missed optimization opportunity: conditional sorting
Bug #4218: Multithreading crash - ConcurrentModificationException evaluating subtyping relationship
Bug #4221: Distinct options for Query.exe from command line help and in Documentation
Bug #4224: Text about Xslt30Transformer uses wrong method name as asDestination(); method is named asDocumentDestination()
Bug #4225: Imprecise type inference for xml-to-json() function
Bug #4228: Setting Feature.SERIALIZER_FACTORY_CLASS fails
Bug #4239: When using a JAXP SchemaFactory, an error in the schema goes unreported
Bug #4242: NullPointerException in checkPlausibility when parsing http://schemas.opengis.net/sos/2.0/sos.xsd
Bug #3261: Duplicate binding slot assignment (switch optimization)
Bug #3711: SCM: inadequate representation of value constraints
Bug #4048: NullPointerException when passing empty sequence as second argument to map:merge
Bug #4052: NullPointerException (no retained static context) during XSLT optimization in 9.8.0.15
Bug #4227: java.lang.NullPointerException when using xsl:catch with @error on undefined errors
Bug #4229: The saxon:system-id() function does not return the correct systemID when the documents contains xi:include
Bug #4237: Assertion error when bytecode generation fails

The following bugs are cleared in 9.9.1.3, issued 2019-05-15 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

Bug #3916: Internal errors evaluating streamable stylesheet functions
Bug #3958: Scheduling algorithm for xsl:for-each/@saxon:threads=N
Bug #3960: Transformation API: supplying lexical XML input and setting the global context item
Bug #4053: Bytecode generation crashes compiling $variable[3]
Bug #4056: object?method() notation for reflexive extension functions does not work when there is an XPathContext parameter
Feature #4070: Provide more options for conversion from Java java.time to XDM date/time values
Bug #4089: TinyTree bulk copy fails with AssertionError when copying final empty element node
Bug #4119: AdjacentTextNodeMerger.process() method is inoperative
Bug #4125: The json-to-xml() function skips calls on startContent()
Bug #4155: <xsl:expose component="mode"> has no effect on implicitly-declared modes
Bug #4158: Broken Maven Artefacts - net/sf/saxon/Saxon-HE/9.9.1-1
Bug #4162: No error at export time if stylesheet calls function-lookup() and target environment (JS, HE) does not support HOF
Bug #4168: Default namespace for calendar attribute of format-dateTime()
Bug #4169: Throws System.NotImplementdException when calling extension function indirectly via package
Bug #4172: Spurious assertion failure caused after another validation error
Bug #4173: XdmNode.toString() on text nodes
Bug #4179: Undocumented XSD extension xs:pattern/@saxon:flags
Bug #4182: No trace execution point around main XQuery body expression
Bug #4185: Saxon does not check that nodes returned by an IntegratedExtensionFunction belong to the right Configuration
Bug #4187: Failures using character maps with method="adaptive"
Bug #4194: CollationKey for AlphanumericCollator always does codepoint collation
Bug #4196: Navigation of wrapped DOM: merging of adjacent text nodes
Bug #4197: Default namespace for QNames in xsl:catch
Bug #4205: Mode with on-no-match="deep-copy" - type annotations dropped?
Bug #4207: Poor error message: FORG0001: Required attribute @Q{http://www.example.com/ns/ma... is missing on element <notation-elem>
Bug #4208: In XSLT value templates, closing brace is not recognized when followed by backtick
Bug #4211: Unnecessary error log message when using file:move() extension function
Bug #4214: Incorrect error message from XSD validation when an element in the content model is absent
Bug #4215: fn:xml-to-json#2 is not streamable




The following bugs are cleared in 9.9.1.2, issued 2019-03-12 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

Bug #3956: Incorrect base URI for element nodes within a secondary result document
Bug #4054: Spurious "ambiguous match" warning when a reloaded stylesheet contains a template rule with an overlapping union pattern
Feature #4059: Simple maps with string keys
Bug #4086: Type checking: poor diagnostics on "cannot atomize a map"
Bug #4091: Function with declared argument type of xs:error can be successfully called
Bug #4098: Indentation should be suppressed for mixed content in schema-validated output
Bug #4099: Possible two small bugs in the handling of ErrorListener
Bug #4104: Static error not detected: reserved namespace in extension-element-prefixes
Bug #4106: function-available(), if executed at run-time, does not check the syntax of the supplied QName
Bug #4107: XTSE0090: Attribute @select is not allowed on element <xsl:evaluate>
Bug #4108: Saxon-EE crashes when optimizing stylesheet with "too many" user functions
Bug #4110: processing-instruction does not contain character when input matches '^\s+[a-z]$'
Bug #4111: [.NET] xsl:function/@override="no" does not work
Bug #4114: XSLT pipeline : Error XPDY0002 - The context item for axis step fn:root(…)/element() is absent
Bug #4115: Value of $err:code in try/catch when no error code has been set
Bug #4117: java.lang.AssertionError : Target of component reference variable keywords is undefined (caused by inlining function calls across a package boundary)
Bug #4118: Bytecode: incorrect calls on Controller.allocateSequenceOutputter()
Bug #4120: Failure during execution of an exported-and-reloaded stylesheet (regression in 9.9.1.1)
Bug #4121: UnsupportedOperationException when writing to DOMResult
Bug #4122: sql:execute leaves open cursors in Oracle
Bug #4123: ClassCastException running analyze-string after exporting/reloading and generating bytecode
Bug #4124: When building the tree used for validating XSD assertions, an extra endElement event is issued
Bug #4126: MetaTagAdjuster replicates namespace bindings
Bug #4127: parse-xml-fragment fails when -catalog is in use
Bug #4128: Wrong result from XQuery involving saxon:stream
Bug #4129: xsl:strip-space elements="xsl:*" fails saying xsl prefix refers to a reserved namespace
Bug #4130: `NamePool.getUnprefixedQName(fingerprint)` returning a name including a prefix
Bug #4132: xsl:function does not accept an EQName containing no colon
Bug #4133: XQuery 3.1 err:additional not bound
Bug #4134: XQuery: default collation and starts-with causes fatal error cannot be cast to net.sf.saxon.lib.SubstringMatcher
Bug #4137: XsltTransformer.transform() starting at xsl:initial-template
Bug #4140: Namespace aliasing creating attribute name conflicts.
Bug #4142: Diagnostic context stack not maintained by xsl:result-document
Bug #4143: Default for Feature.STRIP_WHITESPACE changed in 9.8 and doesn't match the documentation
Bug #4144: $err:column-number in xsl:try/xsl:catch
Bug #4145: With the -a option on the command line, parameters do not take effect
Bug #4146: Error not caught by try catch, because an expression is loop-lifted outside the xsl:try
Bug #4149: "//following::text()" causes ClassCastException
Bug #4150: NullPointerException in streamed GeneralComparison
Bug #4152: Initial template must be public or final: XTDE0040 not reported
Bug #4153: StylesheetPackage.isRootPackage()
Bug #4157: Accepting a mode as final prevents overriding
Bug #4159: current-output-uri() should be empty when in a user-defined function
Bug #4160: current-output-uri() should be empty while evaluating a pattern
Bug #4166: UnsupportedOperationException when writing to TextWriterDestination on .NET
 

 The following bugs are cleared in 9.9.1.1, issued 2019-01-21 (this includes bugs that appear only in the commercial
 versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
 https://saxonica.plan.io/projects/saxon/issues :


Bug #1564: Incorrect NaN comparisons using bytecode generation
Bug #3261: Duplicate binding slot assignment (switch optimization)
Bug #3664: .NET API design: new Processor(Stream) does not allow a base URI
Bug #3711: SCM: inadequate representation of value constraints
Bug #3969: XdmMap - consistency of get(), containsKey(), put(), remove()
Bug #3973: .NET API: XPathCompiler, XQueryCompiler, and XsltCompiler have a Processor property with a setter method.
Bug #4007: Type subsumption of union types
Bug #4008: Descendant iterator over TinyTree with grafted subtrees and textual elements
Bug #4009: Precomputed number formatter when xsl:number loaded from SEF file
Bug #4010: XSLTController.getStreamingReceiver - thread-safety
Bug #4011: PackageLibrary - thread safety
Bug #4012: Configuration Feature.XPATH_VERSION_FOR_XSLT
Bug #4013: Result type of Steps.path()
Bug #4014: Bytecode generation problems (inadequate testing)
Bug #4015: GeneralComparison - missed opportunities for optimization
Bug #4016: Setting the threshold for generating bytecode
Bug #4017: XQuery static type analysis does not take account of global context item declaration
Bug #4019: Problems with reuse of Transformer instances
Bug #4021: ClassCastException setting an integer-valued feature from the command line
Bug #4023: Bytecode generation for `filter[normalize-space()]`
Feature #4024: saxon:schema() extension function: representation of enumeration facet
Bug #4025: Pattern optimizer for contains() ignores collation
Bug #4027: Extreme values for second argument of round()
Bug #4028: When streaming, trace() function produces no output
Bug #4029: saxon:path() is broken in 9.9
Bug #4032: In-situ validation does not expand defaults for element nodes
Bug #4033: XQuery Update: indexes are not reset after an updating query
Bug #4037: XSLT 3.0 test case error-FODC0002a failing under some circumstances
Feature #4038: TinyTree statistics held in static, not in the Configuration
Feature #4039: Optimizing format-integer() when the picture/language are known statically
Bug #4040: Hyphenation of spelled-out English numbers
Feature #4042: Generate bytecode for computing sort keys
Bug #4043: saxon:schema() model for element declarations: scope.parent is not supplied when the parent is a named model group
Bug #4044: Tail call optimization of xsl:call-template with bytecode generation
Bug #4045: Null pointer exception when compiling stylesheet with template containing specific XSLT instructions
Bug #4046: Bytecode is not generated for stylesheets that are exported and then reloaded.
Bug #4047: Unrecognized collations in default-collation attribute
Bug #4048: NullPointerException when passing empty sequence as second argument to map:merge
Feature #4049: Shadow attributes in the Saxon namespace
Bug #4050: Internal error : net.sf.saxon.value.StringValue cannot be cast to net.sf.saxon.om.NodeInfo
Bug #4052: NullPointerException (no retained static context) during XSLT optimization in 9.8.0.15
Bug #4055: No stack trace when missing tunnel parameter detected
Bug #4057: Code for allocating slots to xsl:iterate parameters is not present in Saxon-HE
Bug #4060: Tree grafting code not being invoked
Bug #4062: Loading of relocatable SEF files
Bug #4064: NullPointerException in ConfigurationReader
Feature #4066: Tracing of template rule matching
Feature #4067: Enhanced stack trace after dynamic errors: show values of variables
Bug #4076: fn:replace() with unmatched double digit capturing group
Bug #4097: Base URI of a copied node
Bug #4068: Incorrect week number for the last few days in a year
Bug #4069: Error message for invalid base64 crashes Console on .NET
Bug #4071: Copying of line numbers
Bug #4074: Try/Catch overhead because of potential multithreading
Bug #4075: <xsl:for-each saxon:threads="8"> fails with RejectedExecutionException
Bug #4076: fn:replace() with unmatched double digit capturing group
Feature #4078: Fast XPath parsing for simple expressions
Bug #4079: Promotion from xs:anyURI to xs:string
Bug #4081: XdmNode.toString() output changes between 9.8.0.14 to 9.9.0.2
Bug #4088: Serialization with ResultDocumentHandler doesn't take output properties defined with "format" attribute and "xsl:output" or directly as attributes of "xsl:result-document" into account
Bug #4093: xsl:result-document/@format does not accept an EQName
Bug #4095: Template invocations via xsl:next-match and xsl:apply-imports do not appear on the stack trace
Bug #4097: Base URI of a copied node
Bug #4100: Export code assumes there is a "target" (e.g. EE or JS) but this is not the case when doing an "explain"
Bug #4101: In the fn:serialize options parameter, the expected type for saxon:property-order is xs:QName*
Bug #4105: Truncated stack trace on dynamic error in user function

The following bugs are cleared in 9.9.0.2, issued 2018-11-07 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues :

Bug #3919: Saxon validation fails where Xerces succeeds
Bug #3923: Invalid result-document output in Saxon-HE-9.9.0-1
Bug #3925: Validation that succeeds under 9.8 fails under 9.9
Bug #3926: Stylesheet with saxon:threads="1" produces no output
Bug #3927: Multi-threading problems using Saxon-EE xsl:result-document with calls on last()
Bug #3931: The extension attribute xsl:result-document/@saxon:asynchronous is not recognized
Bug #3932: accumulator-before not working correctly with streaming and xsl:result-document in Saxon 9.9. EE
Bug #3935: command line catalog option
Bug #3936: xsl:call-template not executed under Saxon-EE
Bug #3937: Spurious warning from xsl:accumulator/@saxon:trace
Bug #3940: Streamable accumulator: value must be grounded
Bug #3941: Post-descent accumulator value not available within template rule for the matched element
Bug #3942: Duplicate component ID in generated SCM file
Bug #3943: fn:innermost() optimization not working
Bug #3956: Incorrect base URI for element nodes within a secondary result document
Bug #3965: fn:transform: saxon:schema-validation in vendor-options
Bug #3970: Parsing document {}, try {}, …
Bug #3974: Configuration options for generating bytecode
Bug #3979: Synchronization of xsl:message
Bug #3980: Incorrect type inference for map:merge() function
Bug #3983: strange behaviour of not in predicate
Bug #3984: Thread safety of index information held by KeyManager
Bug #3986: Applying a string-join(count(x)) expression in a root template completely crashes Saxon 9.9.0.1J
Bug #3992: Overriding a variable in a used package fails if neither variable has an explicit declared type
Bug #3993: Dynamic disabling of xsl:evaluate
Bug #3994: NullPointerException when using xsl:result-document
Bug #4001: unparsed-text-available(()) throws a type error
Bug #2060: Use -T option when streaming
Bug #2321: Function inlining
Feature #3175: Allow debugging Saxon in streaming mode
Bug #3754: Multiple close() attempts on StreamResult
Bug #3764: Optimizing GeneralComparison to ValueComparison
Bug #3814: "Class not found" attempting to load generated bytecode
Bug #3920: Problems using xsl:result-document with no href attribute
Bug #3921: Bytecode generation problems in XSD validation
Bug #3922: OutputURIResolver.close() is not called in 9.9
Bug #3928: xs:import-schema with no namespace attribute reports no error if target schema document has a targetNamespace
Bug #3930: No longer working in 9.9.0.1: executable.getUnderlyingCompiledStylesheet().getOutputProperties().getProperty(OutputKeys.ENCODING)
Bug #3933: Inappropriate type warning for absent xsl:otherwise branch
Bug #3934: Streamability analysis problem SXST0060
Feature #3938: Create a virtual tree with modified base URI and/or system ID
Bug #3945: Poor optimization of `$doc1/descendant-or-self::node()/child::node()`
Bug #3949: Diagnostics on bytecode generation errors
Bug #3954: Multithreaded xsl:for-each with saxon:threads: use of last()
Bug #3959: Spurious warning: the attribute axis starting at a text node will never select anything
Bug #3966: Internal error evaluating template rule (override-v-015)
Bug #3968: XdmArray.append() accidentally overrides XdmValue.append()
Bug #3971: XdmMap.values() documentation
Bug #3972: XPathExpression.evaluateSingle() does not close the iterator
Bug #3981: No error when the value of a static parameter is supplied at execution time
Bug #3982: Raw type Item used in 'XPathExpression.evaluate' method signature
Bug #3996: Steps.atomize() does not handle atomization of arrays
Bug #3998: Context path in validation reports
Bug #4002: Regex caching mechanism
Bug #4004: Pull-mode walking of TinyTree extensions
Bug #4006: Implementation of arrays


The first release in this series, 9.9.0.1, was issued on 27th September 2018.

Bugs can be reported, and known bugs inspected, on the Saxon community site at 
https://saxonica.plan.io/projects/saxon

The sourceforge bug tracker is no longer maintained.