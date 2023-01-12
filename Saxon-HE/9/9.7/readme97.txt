==============================

Welcome to the Saxon-HE 9.7 release notes of the open-source edition of Saxon.

The latest major release of Saxon-HE is 9.8, but we are still committed to maintaining the 9.7 release.

It is available for the Java and the .NET platforms.

The current maintenance release is Saxon-HE 9.7.0.21.

The documentation for Saxon is at http://www.saxonica.com/documentation/
and includes a detailed list of changes for each release.

For the Java platform, download file SaxonHE9-7-0-21J.zip. Installation instructions are at:

http://www.saxonica.com/documentation/index.html#!about/installationjava

The file saxon-resources9-7.zip contains documentation, sample files, test drivers and other miscellaneous resources. 
It is common to both platforms, and is not normally updated when new maintenance releases appear.

The file saxon9-7-0-21source.zip contains source code for both platforms; a new version is produced with each
maintenance release. Source code with the latest patches can also be obtained from a Subversion repository
maintained at https://dev.saxonica.com/repos/archive/opensource. The Subversion repository on the SourceForge site is no longer maintained.

The following bugs are cleared in 9.7.0.21, issued 2017-12-05 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #3508: Internal error evaluating template rule (involves xsl:next-match)
Bug #3520: Adding file attachments in saxon:send-mail()
Bug #3527: Another bug with XSD 4-field identity constraints
Bug #3534: Simple map operator, fn:min
Bug #3546: fn:remove, 2nd argument different to xs:integer
Bug #3528: General comparison, reversing sequences
Bug #3490: XSD identity constraints with exactly 4 fields will validate incorrectly	
Bug #3478: Stackoveflow in UserComplexType.getDescendantElementCardinality
Bug #3467: Difference in evaluation between PE and EE (Saxon 9.7.0.20)
Bug #3459: Calling XQuery-defined functions directly from Java: obsolete documentation	Actions
Bug #3409: Crash in Xslt.cs when initialContextNode == null
Bug #3401: File Handle Leaks when a stylesheet module is included/imported more than once
Bug #3376: DecimalValue.Value and GetDecimalValue gives wrong value due to locale settings
Bug #3368: java.lang.NumberFormatException thrown when creating XdmAtomicValues with a Decimal in .NET
Bug #3365: Context is lost if a trace listener is added
Bug #3332: XdmITem.GetStringValue() missing from .NET

The following bugs are cleared in 9.7.0.20, issued 2017-07-27 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Support #3233: Difference in behavior between Saxon 9.6 and 9.7
Bug #3287: Performance bottleneck in SequenceType
Bug #3346: IndexOutOfBoundsException constructing an error message
Bug #3348: Regression in Saxon 9.7 XSLT when normalizing namespaces on large XML
Bug #3359: .NET XQuery: Unable to pass an external variable to XQueryEvaluator
Bug #3360: Incorrect parsing of date/time with timezone offset -00:MM

The following bugs are cleared in 9.7.0.19, issued 2017-07-07 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :


Bug #3250: collection() with on-error=ignore stops after the first failure (with no error)
Bug #3254: Documentation error in 9.8.0.1 for xsl:mode (shallow copy)
Bug #3258: Predicate [not(self::pb)] on current-group() not working with streaming and for-each-group group-ending-with
Bug #3261: Duplicate binding slot assignment
Bug #3262: Problems validating XSLT with Saxon JS extensions using elements factory from "com.saxonica.ee.extfn.js"
Bug #3269: NullPointerException using absent extension instruction with xsl:fallback
Bug #3270: NullPointerException with missing xsl:namespace-alias/@stylesheet-prefix
Bug #3272: NullPointerException when xsl:key has no @name attribute
Bug #3287: Performance bottleneck in SequenceType
Bug #3290: Using key#3 with composite key - third argument ignored
Bug #3294: Thread contention on LRUCache.get
Bug #3317: <xsl:output method=""/> raises java.lang.StringIndexOutOfBoundsException
Bug #3090: PTreeWriter / PTreeReader round-trip loses the content of comments and PIs
Bug #3129: NPE in "TinyBuilder" when running XQuery
Bug #3178: Updates for Saxon sample resources
Bug #3194: NPE: Internal error: expression . has no retained static context
Bug #3195: Duplicate binding slot assignment
Bug #3197: Diagnostics on "Cannot compare xs:integer to xs:string"
Bug #3199: IllegalStateException using a sef package when a namespace contain a space character
Bug #3200: StackOverflow (infinite recursion in optimizer)
Bug #3201: Identity Transformer does not pass unparsed entities through
Bug #3207: @default-validation should not affect xsl:source-document
Bug #3208: Static base URI of query with -qs on command line
Bug #3210: Regular expression with flags="i;n"
Bug #3211: ArrayIndexOutOfBoundsException in ARegexIterator.computeNestingTable with complex regex
Bug #3212: NullPointerException evaluating if (A = B to C)
Bug #3217: Warning: bytecode generation fails for try/catch
Bug #3219: IntersectExceptExprP pattern default priority calculated incorrectly
Bug #3220: Error message for xsl:merge with streamable says "Streaming on xsl:merge-source is possible only when @for-each-stream is used", attribute is named @for-each-source now
Bug #3222: Inefficient string comparison
Bug #3224: For xsl:number/@count="." Saxon 9.7 reports XTSE0340: Token "." not allowed here in an XSLT 2.0 pattern
Bug #3225: Adaptive and JSON output methods using JAXP interfaces
Bug #3226: Effect of current-group() when absent: SaxonHE 9.6 vs 9.7
Bug #3227: Saxon-specific serialization parameters in xsl:result-document
Bug #3229: Saxon 9.7 fails to compile xsl:output/@json-node-output-method
Bug #3232: Character maps with JSON serialization
Support #3233: Difference in behavior between Saxon 9.6 and 9.7
Bug #3234: Provide some kind of API to set static parameter values when transforming
Bug #3235: IntegerRangeTestCompiler does not check endpoints for ()
Bug #3236: Getting and setting the XQuery version in the Configuration object are not symetrical
Bug #3239: PullToStax.getNamespacePrefix(int i)
Bug #3241: Subclassing DOMSource (Compatibility with xmlunit?)
Bug #3242: Static type checking error with document-node()
Bug #3243: Variables incorrectly in-lined into xsl:on-completion
Bug #3244: The -now option on the Query command line has no effect
Bug #3245: Incorrect type inference for ListCastableFunction
Bug #3247: Function-lookup failing on .NET with an ArrayStoreException
Bug #3275: On .NET, included and imported stylesheet modules get locked
Bug #3068: Cannot output a namespace node for the default namespace when the element is in no namespace




The following bugs are cleared in 9.7.0.18, issued 2017-04-05 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #3050: EXPath Archive functions
Bug #3070: NullPointerException at gen_CompiledFilterIterator_...matches... for selectors and abstract types
Bug #3108: Configuration file documentation and schema improvements
Bug #3120: Streaming not working from JAXP Transformation API
Bug #3128: Document Projection filter has diagnostic tracing enabled
Bug #3136: function available-system-properties() does not return the xsl:supports-higher-order-functions property
Bug #3138: With XSLT-invoked validation, duplicate xs:ID value is not properly reported
Feature #3141: fn:parse-xml should respect configuration's parse options
Bug #3143: Loading the compiled form of a stylesheet which uses ?* on an array
Bug #3144: java.lang.ClassCastException: com.saxonica.ee.optim.SwitchExpression cannot be cast to net.sf.saxon.expr.instruct.TailCallReturner
Bug #3150: allowing empty, exactly-one, count
Bug #3151: Streaming: reference to XSLT spec needs updating
Bug #3152: XQ: Collection filtering is wrong inside a loop if GENERATE_BYTE_CODE=off
Bug #3156: No binding slot for global reference in xsl:key match pattern
Bug #3157: more-books.xml and rename-to-lowercase.xsl files missing from saxon-resources zip
Bug #3158: The -stats option on com.saxonica.Validate command line seems to be broken
Bug #3159: Possible concurrency bug when using strip-space
Bug #3162: Incorrect captured groups in fn:analyze-string
Bug #3164: java.lang.ClassCastException: net.sf.saxon.tree.tiny.TinyAttributeImpl cannot be cast to org.w3c.dom.Attr
Bug #3165: Inefficiency related to xsl:strip-space
Bug #3166: Categories.xml file is read unnecessarily
Bug #3168: Sample XPathExampleSA fails with UnsupportedOperationException
Bug #3169: SystemIdMap not properly working?
Bug #3173: QT3 test case same-key-026
Support #3174: "xslt30.xsd" missing from Saxon extra resources samples folder
Bug #3177: NPE when compiling XSLT with Saxon 9.7
Bug #3179: Link to command line documentation is wrong
Bug #3180: Documentation app navigation problems on computers with touch screens
Bug #3182: NPE when creating a transformer over an xsl:package
Bug #3185: Failure setting XQueryCompiler.XQueryLanguageVersion to "1.0"
Bug #3188: Internal Saxon error (local variable encountered whose binding has been deleted)
Bug #3189: XMark regression in q9 performance
Bug #3191: Expression property NOT_UNTYPED_ATOMIC set incorrectly
Bug #3192: ByteCode generation failure for IndexedFilterExpression

The following bugs are cleared in 9.7.0.15, issued 2017-02-07 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :


Bug #2779: Pre-checking source code for used packages is unreliable
Bug #2781: XSLT 3.0 specification change: xsl:use-package is now allowed within included modules
Bug #2962: Lax validation doesn't use the XML namespace schema
Bug #2980: xml-to-json() function is not streamable
Bug #3051: NullPointerException no retained static context (using map lookup)
Bug #3057: When running from Transform command line, whitespace stripping is not done during document building
Bug #3058: Generated global variables include duplicates
Bug #3060: XMLSchema.dtd missing from catalogue
Bug #3061: saxon:key-map problems
Bug #3062: Validation of element node ignores xsi:type attribute
Bug #3064: Incorrect optimization of xsl:attribute using default namespace
Bug #3068: Cannot output a namespace node for the default namespace when the element is in no namespace
Bug #3069: [Saxon 9.7] Internal Saxon error: local variable encountered whose binding has been deleted
Bug #3072: NullPointerException if EXPAND_ATTRIBUTE_DEFAULTS off and selector on attribute
Bug #3073: Documentation missing for serialization section of configuration file
Bug #3075: resolve-uri() with UNC failing to work
Bug #3076: Streaming failure when the consuming expression in xsl:choose is a condition after the first
Bug #3078: Streaming failure with xsl:result-document when an attribute of the instruction is consuming
Bug #3079: NPE when validating an attribute set that refers an undeclared attribute set
Bug #3080: Regression on test program for #2635 - threads left
Bug #3083: Multithreading issue when xsl:result-document nested within xsl:analyze-string
Bug #3088: annotatedConfig.xsd does not allow xslt/@initialMode in {uri}local form
Bug #3091: XLink schema imported repeatedly
Bug #3092: Overlapping union types wrongly classed as disjoint
Bug #3093: UserFunctionReference.copy() returns the original expression unchanged
Bug #3094: Internal error messages are output to stderr
Bug #3096: When XSD 1.1 is enabled, year-from-date("-1200-01-01") gives -1201.
Bug #3101: parse-xml-fragment() does not work under .NET
Bug #3103: Bytecode not being generated for simple predicates
Bug #3104: StringIndexOutOfBoundsException thrown by ICUNumbererPE.getLocales()
Bug #3105: system-property('xsl:is-schema-aware') called within use-when always returns false
Bug #3106: Problems applying fold-left() to random-number-generator()
Bug #3111: NPE in ContentValidator.makeValidatorForType(ContentValidator.java:496), abstract type
Bug #3112: Document Projection is not working properly
Bug #3114: Query with -stream returning streamed nodes
Bug #3116: NPE for map/array lookup expression when byte code generation is turned on
Bug #3119: No error when xsl:mode has children
Bug #3121: NullPointerException in XQuery when defaultCollationName is not a known collation
Bug #3122: last() not computed correctly when processing sequence constructed from variable
Bug #3123: Validation error text for ErrorListener on DynamicQueryContext is different (not informative) than that on Configuration
Bug #3124: GroundedIterator.materialize() returns the whole sequence, not just the residue
Bug #3126: Streamed evaluation of square array constructor crashes
Bug #3050: EXPath Archive functions
Bug #3070: NullPointerException at gen_CompiledFilterIterator_...matches... for selectors and abstract types


The following bugs are cleared in 9.7.0.14, issued 2016-12-02 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #3049: saxon:current-mode-name() returns non-empty
Bug #3052: Performance issue - differences between HE/PE/EE especially on .NET
Feature #2621: Need an option to run xsl:stream in non-streaming mode
Bug #2931: Xslt30Transformer.applyTemplates() does not apply xsl:strip-space rules
Bug #3023: Collection resolver assumes platform default encoding for JSON and unparsed text resources


The following bugs are cleared in 9.7.0.13, issued 2016-11-28 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #2982: net.sf.saxon.lib.TraceListener.open(Controller) doesn't get called for an XQuery Update
Bug #3017: Schema for the fn namespace
Bug #3022: Multithreading error: ClassCastException at at net.sf.saxon.expr.parser.ExpressionTool.evaluate(ExpressionTool.java:276)
Bug #3023: Collection resolver assumes platform default encoding for JSON and unparsed text resources
Bug #3024: Base URI reported for a secondary result document is incorrect.
Bug #3037: Export (SEF) files and C0 control characters
Bug #3038: Internal error: no value for variable using Saxon 9.7.0.11
Bug #3044: Stylesheet export problem with "switch" optimization
Bug #3045: JAXP validation: default error handling should be draconian
Bug #3046: Export problem with xs:NMTOKENS(.) constructor function
Bug #3047: Serialization property saxon:attribute-order not sorting attributes correctly
Bug #3048: NodeOverNodeInfo interface exposes namespace undeclarations

The following bugs are cleared in 9.7.0.12, issued 2016-11-22 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #2807: Operands of LocalParam
Bug #3002: xsl:initial-template in a used package is public
Bug #3006: On .NET, XdmValue.GetList() delivers an unwrapped item if the XdmValue is a singleton
Bug #3010: Streaming and 1.0 compatibility mode
Bug #3013: Whitespace compression not working when there are tabs in the data
Bug #3014: Performance of deep-copy / serialization
Bug #3015: Whitespace stripping using export
Bug #3018: Encoding issue with SEF files
Bug #3019: NullPointerException executing an exported/reimported stylesheet containing an ambiguous extension function call
Bug #3022: Multithreading error: ClassCastException at at net.sf.saxon.expr.parser.ExpressionTool.evaluate(ExpressionTool.java:276)
Bug #3027: Duplicated starting element in trace
Bug #3028: Wrong line number for xsl:variable in XSLT Trace
Bug #3030: AccessControlException reading the environment variable SAXON_HOME
Bug #3031: Missing location info for an XQuery transformation
Bug #3032: Document constructed using DocumentBuilder.newBuildingContentHandler() has no base URI
Bug #3034: XQuery Function line number is incorrectly reported
Bug #3035: Spec change (bug 29981): overriding tunnel parameters
Bug #3040: Setting a custom XmlResolver on a compiler does not work
Bug #3041: xsl:override of global variable
Bug #3042: fn:unparsed-entity-uri() returns xs:string rather than xs:anyURI

The following bugs are cleared in 9.7.0.11, issued 2016-11-22 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

No bug fixes applies to the Saxon-HE version. Patch for bug issue 2962 removed.

The following bugs are cleared in 9.7.0.10, issued 2016-10-21 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #2852: java.util.EmptyStackException in ForEachGroupPartitionAction.startSelectedParentNode when using streamed group-adjacent with composite key
Bug #2920: On an exported/re-imported stylesheet, function-available() fails on fn:collation-key and fn:json-to-xml
Bug #2922: <xsl:apply-templates/> when context item is not a node should give error XTTE0510 but gives XPTY0020
Bug #2924: Using an array in the content expression of an element constructor
Bug #2925: xsl:number optimization not working with "$" in pattern
Bug #2926: Memoization of last remembered number is not thread-safe
Feature #2927: New map:find() function
Bug #2929: Performance regression for whitespace stripping in 9.7
Bug #2932: NullPointerException when an xsl:package contains an xsl:include
Bug #2934: Saxon 9.7 hangs when processing XSLT 3.0 stylesheet using streaming and xsl:iterate/xsl:break with early exit
Bug #2936: format-date/time - fractional seconds - spec clarifications
Bug #2937: Map Constructor syntax: spec clarifications
Bug #2938: map{x: y} instance of function(X) as Y
Bug #2939: Character maps in fn:serialize()
Bug #2940: NullPointerException getting processor version
Bug #2943: Wrong result when apply-templates uses streamed access to evaluate xsl:with-param
Bug #2946: Wrong catch clause is evaluated
Bug #2949: Undetected errors in xsl:global-context-item
Bug #2950: NPE thrown in QT3 test case fn-function-lookup-798
Bug #2951: Incorrect results from analyze-string()
Bug #2952: Support for exponent-separator in XPath API
Bug #2953: UCA collations cannot be used for substring matching
Bug #2958: NullPointerException running a simple streaming query from the command line
Bug #2959: Streamed XQuery fails "no more input required"
Bug #2960: fn:analyze-string produces tree without namespace nodes
Bug #2961: contains("", "*") with a collation that ignores "*"
Bug #2962: Lax validation doesn't use the XML namespace schema
Bug #2963: Configuration feature PRE_EVALUATE_DOC_FUNCTION not working
Bug #2964: Errors in the syntax of xsl:package/@package-version are not reported
Bug #2967: Spec change: maxVariable parameter in UCA collation URI
Bug #2968: Spec change: result of fn:collation-key() must be xs:base64Binary
Bug #2970: Base64 casts: error message
Bug #2971: Empty name attribute causes java.lang.IndexOutOfBoundsException
Bug #2972: NullPointerException with streaming when trying to store copy-of() of current-group() items in map
Bug #2974: Using XPath 3.1 expressions in xsl:evaluate
Bug #2975: Warnings issued during xsl:evaluate don't identify the context
Bug #2976: Exception in thread "main" java.lang.AssertionError: The Label: endBlock has been used but not marked
Bug #2977: Formatting of xs:double values under the adaptive serialization method
Bug #2978: function-lookup() fails on map:merge and map:put
Bug #2979: format-dateTime formatting the year with roman numerals and width modifier
Bug #2983: Serialization: outputting arrays with XML output method
Bug #2984: element-available('xsl:source-document')
Bug #2987: AnchorPattern is a singleton but has local data
Bug #2988: When streaming, xsl:where-populated does not work within xsl:for-each-group
Bug #2989: Problem with streaming of xsl:sequence
Bug #2993: Saxon does not allow multiple annotations (on an XQuery function/variable) that have the same name.
Bug #2994: XdmAtomicValue does not have a usable equals() method.
Bug #2996: Streaming xsl:for-each-goup with grounded population does not allow multiple references to current-group()
Bug #2997: NullPointerException after a validation error while streaming
Bug #2998: closing tag of root element missing when using streamed for-each-group group-adjacent
Bug #2999: Spec change in map:merge() - duplicates:unspecified becomes duplications:use-any
Bug #3000: Spec change (bug 29917) - @key and @escaped-key allowed on root of input to xml-to-json()
Bug #3001: Spec change: serialization-params of fn:transform() aligned with fn:serialize()
Bug #3003: fn:parse-json - Saxon is not rejecting raw unescaped control characters
Bug #3005: The ToString method on namespace Node fails nunit test


The following bugs are cleared in 9.7.0.8, issued 2016-09-01 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #2840: .NET API documentation does not list constructor for new XdmAtomicValue("string")
Bug #2841: closing tag of result elements missing when using streamed grouping of grounded nodes
Bug #2843: Transformer.URIResolver should default to TransformerFactory.URIResolver
Bug #2844: Javadoc: links not being rendered as links
Bug #2845: An exported stylesheet contains a call to IntegratedFunctionCall map:untyped-contains which cannot be re-imported
Bug #2849: Spec change (bug29665): xml-to-json now escapes solidus
Bug #2850: XQuery shows warning: "supplied value has item type xs:error"
Bug #2851: XQuery -explain throws NPE: Internal error: expression () has no retained static context
Bug #2853: FleetingElementNode is not a FingerprintedNode
Bug #2854: Spec change (bug29749): fractional seconds truncated, not rounded
Bug #2855: Spec change (bug 29792): collation argument for fn:sort and array:sort
Bug #2856: Spec change (bug 29723): map:merge - new argument to control handling of duplicates
Bug #2857: Temporary space requirement during TinyTree.condense()
Bug #2859: xsl:number in streamable mode throws java.lang.UnsupportedOperationException: net.sf.saxon.trans.XPathException instead of being detected as not streamable during compilation
Bug #2860: Functions taking an options parameter handle a non-string option incorrectly
Bug #2861: Dates/times with different timezones are considered not equal as map keys
Bug #2862: java.lang.IllegalStateException: net.sf.saxon.expr.sort.SortKeyDefinitionList.getSweep() called when streamability has not yet been computed
Bug #2863: Internal error: expression ("gml:id",...) has no retained static context
Bug #2864: accumulator in streamable mode not working, works fine when changing the mode to streamable="no"
Bug #2865: NPE from fn:replace
Bug #2866: java.lang.NullPointerException during streamability analysis of template matching text node and using xsl:analyze-string
Bug #2867: Local variable $current has not been allocated a stack frame slot
Bug #2868: Better report "PatternSyntaxException"
Bug #2869: problem with streamable mode
Bug #2872: XSLT generates output with undeclared namespace prefix
Bug #2874: EXPath file:parent() NPE on root directory
Bug #2876: .NET has no equivalent to s9api's XsltExecutable.getWhitespaceStrippingPolicy()
Bug #2877: Built-in template rules (for streaming) write copied nodes to the wrong destination
Bug #2878: output order of two xsl:sequences inside xsl:fork is wrong when applying two different modes
Bug #2879: Type checking on function call in xsl:evaluate expression is done too early
Bug #2880: XQuery with saxon:stream fails to fall back to non-streaming mode
Bug #2881: Required item type of first argument of collection() is node(); supplied value has item type xs:base64Binary - no file extension
Bug #2882: QuickCompare for numerics fails if whitespace is present
Bug #2883: Regression Error in Saxon 9.7.0.4: Internal Error Evaluating Template Rule
Bug #2893: Java-to-XDM conversion will convert a Java Map to an XDM Map, but not in Saxon-HE
Bug #2894: Constructor XdmExternalObject(String, ItemType) is useless
Bug #2895: Only one error reported by an "every $i satisfies..." assertion
Bug #2896: Avoid reporting to StandardErrorHandler a caught exception from parse-xml()
Bug #2897: Tree used for XSD assertion testing has superfluous root node
Bug #2898: The second argument of saxon:serialize must either be a string literal, or an xsl:output element
Bug #2899: StaxToEventBridge Incorrectly Calling getText() for PI data
Bug #2900: Exception cause retention in StAX -> pull API translation
Bug #2901: StaxToEventBridge fails to retain unused namespace declarations
Bug #2902: StreamWriterToReceiver.getNamespaceContext null rootNamespaceContext
Bug #2905: Static HTML documentation Javadoc links not being rendered as links
Bug #2906: xsl:stream becomes xsl;source-document
Bug #2908: Overriding template rules in a package loaded from a stylesheet export file
Feature #2909: Request for additional event + StAX API property getters
Bug #2911: After export/import of a stylesheet, reference to a global variable from within an accumulator rule fails
Bug #2914: Concurrency Issue: Internal error evaluating template
Bug #2915: Casting to a restricted union type
Bug #2916: load-xquery-module should raise an error for an unknown/unsupported XQuery language version
Bug #2917: fn:serialize, when the options are given as a map, should ignore any unknown options
Bug #2918: Handling of special characters in an EQName
Bug #2919: Spec change: XQuery pragmas in no namespace
Bug #2921: Wrong error code for duplicate keys in xsl:map

The following bugs are cleared in 9.7.0.7, issued 2016-07-15 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #2642: NPE when using net.sf.saxon.event.EventSource in Saxon 9.7
Bug #2737: Failure to reload an exported streaming stylesheet
Bug #2753: xsl:stream within extracted global variables
Bug #2783: Bytecode: Missing code in IntegerRangeTestCompiler
Bug #2789: File overwritten with empty file by XQuery Update
Bug #2795: Error message "Value of {cdata-section-elements} must be a list of QNames in '{uri}local' notation"
Bug #2804: ArrayIndexOutOfBoundsException when reloading an XSLT export file containing a reflexive extension function call
Bug #2805: Incorrect code in LocalVariableReference.copy()
Bug #2806: Incorrect code in FLWORExpression.copy()
Bug #2809: Docbook error: XTDE1400: Namespace prefix 'exsl' has not been declared
Bug #2810: ByteCode generation failure during compilation in 9.7
Bug #2812: 	Incorrect type analysis of non-executed xsl:for-each-group body
Bug #2814: current-merge-group() in nested xsl:merge
Bug #2815: NullPointerException with Saxon EE 9.7.0.6 with stylesheet using xsl:merge
Bug #2817: Streamability of path() function
Bug #2818: xsl:next-match as last instruction in a named template causes IndexOutOfBoundsException
Bug #2819: NullPointerException with with stylesheet using xsl:stream and xsl:for-each-group/@starting-with
Bug #2821: XSLT 3.0 stylesheet using xsl:stream working correctly in Saxon 9.6 EE gives wrong result in 9.7 EE while emitting warnings XPTY0004
Bug #2824: StringIndexOutOfBoundsException: String index out of range: -3 exception thrown
Bug #2825: XQuery performance degradation with Saxon-HE 9.7.0.6
Bug #2827: When Java security policy does not allow multithreading
Bug #2828: Xslt30TestSuiteDriver incorretly reports some XSLT30 tests as failures under XSLT20
Bug #2830: position() inside of xsl:for-each-group select="copy-of(root/items/item)" group-adjacent="foo" in streamed mode is wrong
Bug #2831: Streamability analysis for "/" wrong when context posture is grounded
Bug #2832: Error XTDE1061: "There is no current group" inside of xsl:for-each-group in streamed mode
Bug #2834: Requirement to expose getLineNumber and getColumnNumber on .NET XdmNode
Bug #2835: Problems with sql extension functions
Bug #2836: No transmission filter available for xsl:copy-of
Bug #2838: Redundant streaming messages
Bug #2839: saxon:stream() fails "Cannot execute xsl:stream when optimization has been disabled" in XQuery



The following bugs are cleared in 9.7.0.6, issued 2016-06-17 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :


Bug #2568: Streamability of $map($key) versus map:get($map, $key)
Bug #2606: Failure to allow debugging of global variables in the applyTemplate path
Bug #2634: XQuery using saxon:stream fails when falling back to non-streaming and byte code generation is in effect
Bug #2660: DelegatingErrorListener
Bug #2707: Performance regression compiling very large stylesheets
Support #2738: string-join implementation always uses XPath 3.1 implementation
Bug #2740: map function create still exists
Bug #2741: QT3 tests case failing: Pragma in no namespace gives error XQST0079
Bug #2749: Type error XPTY0004: Required item type of first argument of collection() is node(); supplied value has item type xs:base64Binary
Bug #2750: Setting of fileExtension on configuration file does not take effect
Bug #2755: java.lang.IllegalStateException thrown when creating a pipeline
Bug #2756: NullPointerException in TypeHierarchy.relationship using xsl:value-of on a map
Bug #2757: No warnings for "impossible" identity constraints in XSD
Bug #2758: Redundant code for computing special properties of a system function call
Bug #2759: saxon:analyze-string() does not work in 9.7
Bug #2760: Documentation of saxon:compile-stylesheet mentions spurious $precision argument
Bug #2761: Spec change (bug 29660) for map:remove and array:remove
Bug #2762: saxon:key-map() - second parameter has required type document-node()
Bug #2763: fn:key() - optimization not working
Bug #2764: Fourth argument of saxon:send-mail() is optional
Bug #2767: XSLT 3.0 mode with on-no-match="shallow-copy" does not copy namespace nodes
Bug #2768: saxon:validate can return an empty sequence
Bug #2769: expath:base-dir and current-dir functions are not included in the documentation
Bug #2770: Internal error evaluating template rule (IndexOutOfBoundsException)
Bug #2773: xsl:package and @name required at top level
Bug #2774: xsl:override : overriding a function with no declared return type
Bug #2775: XSLT packaging: using a compiled package from the command line
Bug #2776: xsl:override : indirectly called function does not invoke overridden function
Bug #2777: NPE binding xsl:original when the base function does not exist
Bug #2778: saxon:assign is incompatible with multi-threading
Bug #2780: No error if xsl:use-package appears in an imported module
Bug #2782: saxon:next-in-chain fails on 9.7
Bug #2784: Spec change: new function array:put
Bug #2785: Spec change: fn:random-number-generator() accepts empty sequence as argument
Bug #2786: NullPointerException handling duplicates in json-to-xml
Bug #2787: xml-to-json() - handling of duplicate keys
Bug #2788: xsl:strip-space is not applied to the results of collection()
Bug #2790: WhitespaceStrippingPolicy has no effect when doing schema validation or DTD validation
Bug #2791: Whitespace stripping for the doc() and document() functions should depend on which package the function appears in.
Bug #2792: Overriding a template with no declared visibility succeeds when it should fail
Bug #2793: Tail call of function in used package drops component information
Bug #2794: Spec change: xsl:on-empty should treat zero-length strings as vacuous
Bug #2797: XSLT Stylesheet export fails if stylesheet uses saxon:assign or saxon:while
Bug #2798: NullPointerException running an exported stylesheet that uses saxon:evaluate
Bug #2799: Invalid type name in export files for external Java objects
Bug #2800: XsltExecutable.explain() crashes on a stylesheet that has been exported and reloaded
Bug #2801: Infinite recursion in LetExpression.optimize()
Bug #2802: Return type of fn:random-number-generator()?next() is incorrect



The following bugs are cleared in 9.7.0.5, issued 2016-05-12 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :


Bug #2674: Broken links on Saxon on .NET section in the HTML version of the documentation
Bug #2679: XSLT transformation is taking 15% more on 9.7.0-3 vs 9.6.0-1
Bug #2681: System properties: early evaluation
Bug #2685: Incorrect type inference in call on distinct-values()
Bug #2686: QT3 test case filter-limits-003 fails with bytecode feature
Bug #2688: xsl:analyze-string gives wrong results with bytecode enabled
Bug #2689: Output properties empty
Bug #2692: Incorrect output from xml-to-json function, for an empty array inside an array
Bug #2693: java.lang.NoClassDefFoundError: com.saxonica.ee.bytecode.GeneratedCode
Bug #2699: XSLTTestSuiteDriver doesn't exit for some merge tests
Bug #2700: Dynamic function calls in Saxon-HE
Bug #2701: ClassCastException in StandardCollectionURIResolver
Bug #2702: XSL: castable as xs:base64Binary crashes if false()
Bug #2703: ErrorList in SchemaManager not being used in Compile method
Bug #2704: NullPointerException during optimizer tracing
Feature #2705: Add catalog property on the .NET API
Bug #2708: Exporting a literal map
Bug #2709: format time, place argument
Bug #2710: Internal Saxon error: local variable encountered whose binding has been deleted
Bug #2711: UnsupportedOperationException when compiling XPath with JAXP NamespaceContext
Feature #2712: XSLT 3.0 Spec change 29478: xsl:accept/xsl:expose
Bug #2713: NPE from XQuery when catching collection URI resolver exception
Bug #2714: Streamed grouping using xsl:for-each-group group-starting-with and snapshot(current-group())/.. gives different result than unstreamed grouping
Bug #2715: XPath parsing edge cases
Bug #2718: (1,2,3) castable as List fails with type error rather than returning false
Bug #2720: Grouping separators in format-integer()
Bug #2721: Grouping separators in format-number()
Bug #2722: xml-to-json() does not reject an ill-formed document
Bug #2723: Increased memory use in Saxon 9.6 compared to Saxon 9.3
Bug #2724: Single digit hours in parse-ietf-date()
Bug #2725: xml-to-json() problems
Bug #2727: format-date, AIOOB
Bug #2728: Failed to load org.ccil.cowan.tagsoup.Parser
Bug #2730: On Query command line, -TP:profile.html produces incorrect output
Bug #2731: Unknown configuration property http://saxon.sf.net/feature/occurrenceLimits
Bug #2733: Console messages for warnings are prefixed "Error: "
Bug #2735: ArrayIndexOutOfBoundsException while evaluating regular expression
Bug #2736: NullPointerException in Saxon 9.7 evaluating an expression which involves an anonymous type
Bug #2739: Composite keys (xsl:key) give wrong result if bytecode is enabled
Bug #2743: Line numbers of XQuery global variables are out by one
Bug #2745: org.apache.xerces.jaxp.SAXParserFactoryImpl not found in .NET
Bug #2754: Memory leak of an instance model from a schema containing QName valued elements
Bug #2795: Error message "Value of {cdata-section-elements} must be a list of QNames in '{uri}local' notation"
Bug #2789: File overwritten with empty file by XQuery Update
Bug #2799: Invalid type name in export files for external Java objects
Bug #2800: XsltExecutable.explain() crashes on a stylesheet that has been exported and reloaded
Bug #2801: Infinite recursion in LetExpression.optimize()
Bug #2802: Return type of fn:random-number-generator()?next() is incorrect




The following bugs are cleared in 9.7.0.4, issued 2016-03-11 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #2314: Stylesheet Base Uri with spaces causes issues when compiling stylesheet [Saxon.HE 9.6N]
Bug #2566: Streaming does not work from the Transform command line
Bug #2568: Streamability of $map($key) versus map:get($map, $key)
Bug #2574: Bytecode and dynamic call of current-group() and current-grouping-key()
Bug #2581: ErrorListener set in transfomer is not invoked for xsl:message in SaxonPE9.7
Bug #2589: XSLT30 test case validation-0212 fails in Saxon-EE
Bug #2624: Use of predicates when streaming
Bug #2626: Add an equivalent to http://saxon.sf.net/feature/ignoreSAXSourceParser for stylesheets
Bug #2629: java.lang.IllegalStateException: getPosture() called when streamability has not yet been computed
Bug #2630: Wrong output for streamable stylesheet with multiple modes
Bug #2632: Type checking of patterns assumes context item is a node
Bug #2633: 9.7.0.3 regression: XQuery compilation does not terminate
Bug #2635: XQuery using saxon:stream leaves open thread, when closed prematurely
Bug #2638: Whitespace around colon in a MapConstructor
Bug #2639: Calling extension functions: Java class name cannot contain a "q"
Bug #2641: Indirect module imports do not work anymore in Saxon 9.7 HE
Bug #2643: New "Will never select" warning shown in Saxon-EE 9.7 with -opt:10
Bug #2644: 9.7 regression: Deadlock for concurrent instantiation of Configuration and EnterpriseConfiguration
Bug #2646: Redundancy in export file
Bug #2647: Incorrect location for XQuery warnings
Bug #2648: ClassCastException: cannot cast GlobalParam to UserFunction
Bug #2651: select="xs:string(xs:dateTime('9999-12-31T23:59:59.9999999'))" gives => '9999-12-31T23:59:59.:"
Bug #2653: Namespace in report not applied to the outer element when validating multiple documents
Bug #2654: Streaming problem with mixed grounded/striding sequences
Bug #2656: Streaming: mixing striding and grounded posture
Bug #2658: XQuery typeswitch with SequenceTypeUnion reports "Bad parent pointer found in $zz:zz_typeswitchVar"
Bug #2659: Diagnostics for malformed XQuery element constructors
Bug #2661: Nested Location information
Bug #2662: Link to element node in stylesheet needed in location information for errors
Bug #2663: java.lang.AssertionError: Internal error: no value for variable $vv:gg2097915420 at line 11 of
Bug #2664: XQuery optimize leads to stackoverflow
Bug #2665: Validation errors not written to ErrorListener
Bug #2666: JAXP Validator.validate() throws an exception if there are validation errors
Bug #2667: format-date() week-in-month numbering is incorrect
Bug #2668: XQuery: empty constructors
Bug #2669: fn:replace() using q flag, incorrectly raising error FORX0004
Bug #2671: NullPointerException in ValidatingFilter.reportValidationError

The following bugs are cleared in 9.7.0.3, issued 2016-02-18 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #2529: Validation report missing meta-data fragment missing name of XML file
Bug #2548: Property name typo in class StandardLogger
Bug #2552: AssertionError during byte code generation
Bug #2559: Dynamic value of xsl:result-document/@format is ignored
Bug #2560: xsl:fallback is not allowed as a child of xsl:merge
Bug #2561: java.lang.NullPointerException with nested xsl:iterate
Bug #2567: java.lang.NullPointerException with external variable in xsl:iterate/on-completion
Bug #2570: Wrong exit code on error (XQuery command line)
Bug #2571: XQuery group-by leads to "Local variable $x has not been allocated a stack frame slot"
Bug #2578: lang() only considers first hyphen
Bug #2588: xsl:next-match can raise XTDE0565
Bug #2590: NPE when saxon:assign refers to an undeclared variable
Bug #2592: XSD validation regular error events treated as fatal error events
Bug #2593: Space is missed after file name
Bug #2594: NullPointerException when compiling an XPath expression
Bug #2596: On exporting fn:outermost(), knowledge of pre-sorting is lost
Bug #2597: NPE when enabling tracing in XQuery or XPath execution
Bug #2598: IllegalStateException thrown in DITA-OT 1.8
Bug #2599: Schema validation errors are not reported through ErrorHandler
Bug #2601: Prefix allocated when a no-namespace literal result element is exported
Bug #2602: Incorrect TimingTraceListener class in -T: command line documentation
Bug #2604: Incorrect location for XQuery error
Bug #2605: Variable names in export files
Bug #2606: Failure to allow debugging of global variables in the applyTemplate path
Bug #2607: <array> instruction in export output
Bug #2608: Incorrect namespaces in retained static context
Bug #2609: NPE when TemplatesHandler is created with a ProfessionalConfiguration
Bug #2611: Export fails for "X castable as U" where U is a union type
Bug #2613: net.sf.saxon.Transform crashes with IllegalArgumentException: The root node of a tree must be parentless
Bug #2614: Download link for saxon-resources9-7.zip is missing
Bug #2615: Poor diagnostics for FOTY0012
Bug #2616: Streamability of pattern with call to accumulator-before()
Bug #2617: Streamability of a pattern that calls current()
Bug #2618: XTDE0047: Initial mode and template cannot both be defined
Bug #2619: xsl:on-empty treats whitespace as insignificant
Bug #2620: java.lang.NullPointerException: Internal error: expression mergeAdj(()) has no retained static context
Bug #2622: Combining use-character-maps and normalization-form="NFC" attributes produce unwanted output
Bug #2623: xsl:number level="multiple" with count and from patterns matching the same node
Bug #2627: Bytecode generation failing for fn:key#2




The following bugs are cleared in 9.7.0.2, issued 2016-01-19 (this includes bugs that appear only in the commercial
versions of the product). Bugs are listed under the number used on the new Saxonica Community site at
https://saxonica.plan.io/projects/saxon/issues. :

Bug #1921: Interface classes in Javadoc does not contain implementations
Bug #1889: getBaseURI() - performance
Bug #1906: Javadoc for Enumerations
Bug #2285: Saxon.Api documentation: Links to Java classes don't resolve
Bug #2398: Incorrect QName field reported in XMLStreamException in StreamWriterToReciever
Bug #2402: Saxon resources does not contain annotatedConfig.xsd
Bug #2420: EXPath File update to version 1.0
Bug #2498: format-date does not support comma as grouping separator
Bug #2499: format-date large width modifier causes StringIndexOutOfBoundsException
Bug #2500: format-date does not allow # as part of presentation modifier
Bug #2503: AIOOBE using positional variable with Saxon 9.7.0.1
Bug #2504: format-dateTime not acting on supplied Olson time zone
Bug #2505: Saxon 9.7: .php file considered as binary by fn:collection
Bug #2506: Saxon 9.7: NPE from fn:translate on empty sequence
Bug #2509: NPE on executing com.saxonica.StatsTransform from saxon9-stats.jar
Bug #2511: Running Saxon-EE with no license file raises NPE
Bug #2512: Adaptive and JSON output methods from the XSLT command line
Bug #2514: validation-reports.xsd file missing from saxon-resources zip
Bug #2515: -1 value for both line and position values in schema errors
Bug #2516: Schema validation: Fatal errors handled differently
Bug #2519: Third parties jars outdated
Bug #2520: Error codes for array:subarray()
Bug #2521: NPE in resolve-uri() with jar: protocol URIs
Bug #2523: NPE during parseInlineFunction()
Bug #2525: NPE in Serializer.getContentHandler()
Bug #2528: Generated Schema Validation report not valid against validation-report.xsd
Bug #2529: Validation report missing meta-data fragment missing name of XML file
Bug #2530: Ant XSLT task - top-level variables always refer to first input document
Bug #2531: Reflexive extension functions: synthetic methods
Bug #2532: Query Initializer hook invoked too late to set ModuleURIResolver
Bug #2535: Unrecognized version 11
Bug #2536: Failure to check that node returned by extension function has wrong NamePool
Bug #2539: -t option should report when streamed processing is happening
Bug #2540: Unwanted warning with JAXBSource
Bug #2541: Passing list of packages on Transform command line does not work
Bug #2542: EXPath Archive module: ZIP file must have at least one entry
Bug #2543: Javadoc for parameterized types
Bug #2544: saxon:stream() not working under EEQ license
Bug #2545: Invalid slot number: local variables in match pattern with mode="#all"
Bug #2546: XQuery using saxon:stream not streaming in 9.7
Bug #2547: Cannot execute xsl:stream when optimization has been disabled
Bug #2549: XQuery using saxon:stream leaves open thread in 9.7
Bug #2550: No watch found for xsl:element
Bug #2551: Reused source parser may be configured incorrectly
Bug #2552: AssertionError during byte code generation
Bug #2553: java.util.concurrent.ExecutionException for muli-threaded collection processing
Bug #2554: ArrayIndexOutOfBoundsException while evaluating JAXP XPath expression with a variable reference
Bug #2555: Bad parent pointer
Bug #2556: Incorrect copying of subexpressions during FLWOR optimization
Bug #2557: <xsl:evaluate with-params="$map"/> does not seem to work
Bug #2558: Specifying license file location in configuration file
Bug #2559: Dynamic value of xsl:result-document/@format is ignored
Bug #2560: xsl:fallback is not allowed as a child of xsl:merge
Bug #2561: java.lang.NullPointerException with nested xsl:iterate
Bug #2562: Missing end tag in result after using xsl:break
Bug #2563: NPE in export when inferred type involves an aliased namespace
Bug #2564: Vendor function calls not re-imported after stylesheet export
Bug #2565: Inefficient evaluation of exists()
Bug #2567: java.lang.NullPointerException with external variable in xsl:iterate/on-completion
Bug #2569: When the new -nogo option is specified, a source file is still required
Bug #2570: Wrong exit code on error (XQuery command line)
Bug #2571: XQuery group-by leads to "Local variable $x has not been allocated a stack frame slot"
Bug #2573: IncompatibleClassChangeError from bytecode implementing for-each-group()
Bug #2575: Wrong line number on error (XQuery)
Bug #2578: lang() only considers first hyphen
Bug #2580: XQuery: global variables depending on context item
Bug #2582: Internal error: expression element() has no retained static context
Bug #2583: Incorrect export for xsl:number
Bug #2586: NPE in collection()/uri-collection() if there are no query parameters
Bug #2587: NullPointerException loading a packaged stylesheet that refers to unavailable extension functions
Bug #2590: NPE when saxon:assign refers to an undeclared variable
Bug #2591: NullPointerException in Verifiy class thrown from the ActivateSaxon.java class




The first release in this series, 9.7.0.1, was issued on 27 November 2015. 

Bugs can be reported, and known bugs inspected, on the Saxon community site at https://saxonica.plan.io/projects/saxon
The sourceforge bug tracker is no longer maintained.