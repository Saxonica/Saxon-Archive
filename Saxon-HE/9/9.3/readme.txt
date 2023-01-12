Release Notes for Saxon-HE 9.3
==============================

Saxon-HE 9.3 is the latest major release of the open-source edition of Saxon. It is available for both the Java and .NET platforms.

The current maintenance release is 9.3.0.11, issued on 17 November 2011.

For the Java platform, download file saxonhe9-3-0-8j.zip. Installation instructions are at
http://www.saxonica.com/documentation/about/installationjava.xml

For the .NET platform, download file SaxonHE9-3-0-8N-setup.exe. Installation instructions are at http://www.saxonica.com/documentation/about/installationdotnet.xml

The file saxon-resources9-3.zip contains documentation, sample files, test drivers and other miscellaneous resources. It is common to both platforms, and is not normally updated when new maintenance releases appear.

The file saxon9-3-0-11source.zip contains source code for both platforms; a new version is produced with each maintenance release. Source code with the latest patches can also be obtained from Subversion on the SourceForge site.

Release 9.3.0.11 (17 October 2011)
----------------------------------

Releases 9.3.0.9 and 9.3.0.10 were limited releases produced for specific customers to solve specific problems. 
9.3.0.11 is therefore the first general maintenance release since 9.3.0.5.

The major factor making this necessary was an error in the patch for bug 3307404 (which incidentally was omitted
from the list of bugs fixed in 9.3.0.8). The error caused infinite recursion in the class ExpressionTool when the
XSLT current() function was used. Other fixes in this release are:

 3433398 	Error: xsl:result-document allowed in xsl:function 
 3426425 	Installing Saxon on 64-bit .NET platform 
 3426332 	Exception in compiled stylesheets using max() 
 3423925 	ModuleURIResolver fetching the same module twice 
 3423677 	Incorrect JAXP XPath factory information 
 3422928 	Incorrect range variable cardinality for ForExpression 
 3419499 	Incorrect type inference logic for sequence type matching 
 3307404    Calls to current() not resolved at compile time


Release 9.3.0.8 (03 October 2011)
---------------------------------

Releases 9.3.0.6 and 9.3.0.7 were limited releases produced for specific customers to solve specific problems. 
9.3.0.8 is therefore the first general maintenance release since 9.3.0.5.

This release fixes the following problems (note, many of these affect Saxon-PE and/or Saxon-EE only):

3416284	        SAXON_SUPPRESS_INDENTATION
3411093	        NPE caused by namespace code of -1
3408844	        Wrong exception for XdmAtomicValue.getDoubleValue()
3370461	        Base value for indexed lookup is not indexable
3347928	        NullPointerException in saxon:evaluate-node()
3328917	        saxon:doctype doesn't allow text nodes
3324577	        IllegalArgumentException using JAXP TemplatesHandler
3314257	        NPE while looking for license file
3290985	        Compiled stylesheets

Release 9.3.0.5 (21 April 2011)
-------------------------------

This release fixes the following problems (note, many of these affect Saxon-PE and/or Saxon-EE only):

 3291019 	Exception causes stack trace even if caught 
 3290985 	Compiled stylesheets 
 3290950 	use-when="system-property('xsl:is-schema-aware')"
 3287522 	Concurrent query compilation fails with NullPointerException 
 3287432 	Separate compilation of query module with forwards reference
 3205641 	saxon:stream() interacts with other optimizations 
 3204144 	format-integer(1, '#0') failing 
 3200862 	Higher order functions: Value of variable undefined 
 3199872 	xsl:iterate inside xsl:for-each fails ClassCastException 
 3188120 	NPE using xsl:evaluate within xsl:try 
 3188031 	Schema processor crash during error recovery 
 3188011 	XSD11 Rules for local targetNamespace not enforced 
 3188003 	XSD: no check for repeated facets 
 3187976 	XSD11: +0 and -0 not equals 
 3187972 	XSD11: xs:precisionDecimal allows non-ASCII digits
 3187964 	XSD: Value range facets with fixed=true
 3187958 	XSD11: minScaleFacet compared with minLength
 3184807 	IllegalStateException with -explain on xsl:apply-imports
 3183658 	NPE when importing separately-compiled XQuery library module
 3181942 	Function calls with placeholders 
 3176610 	NullPointerException if default namespace unrecognized
 3175418 	Processor.WriteXdmValue ignores serialization properties
 3174927 	Restriction of all model groups with wildcards
 3174922 	anyAttribute intersection with notQName=##defined
 3174866 	ClassCastException outputting cardinality error message
 3169596 	doc-available() outputs error message on XML parse error 
 3161900 	Incorrect default type for "let" expressions 
 3161807 	Incorrect extraction of global variables
 3160155 	Higher order function closures in XSLT 3.0 
 3141754 	ClassCastException in fold-left/fold-right


Release 9.3.0.4 (22 December 2010)
----------------------------------

This release fixes the following problems:

 3141636 	documentNumber limited to 2^32 
 3141217 	collection(()) not allowed 
 3140874 	AIOOB in TinyTree.addNamespace() 
 3139140 	PTree, typed values, and ID/IDREF values 
 3139136 	PTreeWriter fails when document contains namespaces 
 3138542 	Command line messages have wrong link to online docs 
 3134404 	AIOOB when name() called within anonymous function
 3122822 	NPE when xsl:stylesheet is not outermost element 
 3116503 	Dependency on JDK 1.6 (reopened after 9.3.0.2 release)
 

Release 9.3.0.3
---------------

This release was made available to selected customers only for testing

Release 9.3.0.2 (23 November 2010)
----------------------------------

This release fixes the following problems:

 3116503 	Dependency on JDK 1.6 
 3112543 	XSLT 3.0 rejects valid XPath 3.0 constructs 
 3110170 	Default language is Taiwanese 
 3110166 	StreamWriterToReceiver crash


 
Release 9.3.0.1 (30 October 2010)
------------------------------- 

9.3.0.1 was the first release of the 9.3 branch.

For details of new features, see
http://www.saxonica.com/documentation/changes/intro.xml