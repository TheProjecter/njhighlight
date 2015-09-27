### Introduction ###

**njHighligt** is a fork of [JHighlight](https://jhighlight.dev.java.net/).

It adds some new languages, and makes it possible to define a common colour style for all the languages. Individual syntax elements can be overridden for each language.

Supported languages: C++, C#, Groovy, HTML, XHTML, XML, Java, LZX, Pascal, Visual Basic.NET

### Download & source ###

Temporarily, the source code of njHighlight is stored in the SVN repo of [another project](http://code.google.com/p/njcms/source/browse/#svn/trunk/JHighlight). One day I will move it here. The source code is in a NetBeans project.

You can download the ready to use .jar file [here](http://njhighlight.googlecode.com/files/njHighlight-2010-02-24.zip).

### Usage instructions ###

  1. See the [jhighlight site](https://jhighlight.dev.java.net/).
  1. Run the jar file from command line, and you will see how it works.
  1. From your java code...
    1. Use `Renderer r = XhtmlRendererFactory.getRenderer(extension);` to get a renderer.
    1. Use ` r.highlight(...); ` to highlight a source file and produce an XHTML file from it.

### Acknowledgements ###

njHighlight is only a minor improvement over jhighlight, which was originally developed by:
  * Geert Bevin
  * [Omnicore Software](http://www.omnicore.com/)
This program makes extensive use of [JFlex](http://jflex.de/).