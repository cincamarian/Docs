

PatternContextLinearExclude Class
=================================





Namespace
    :dn:ns:`Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts`
Assemblies
    * Microsoft.Extensions.FileSystemGlobbing

----

.. contents::
   :local:



Inheritance Hierarchy
---------------------


* :dn:cls:`System.Object`
* :dn:cls:`Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContext{Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinear.FrameData}`
* :dn:cls:`Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinear`
* :dn:cls:`Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinearExclude`








Syntax
------

.. code-block:: csharp

    public class PatternContextLinearExclude : PatternContextLinear, IPatternContext








.. dn:class:: Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinearExclude
    :hidden:

.. dn:class:: Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinearExclude

Constructors
------------

.. dn:class:: Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinearExclude
    :noindex:
    :hidden:

    
    .. dn:constructor:: Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinearExclude.PatternContextLinearExclude(Microsoft.Extensions.FileSystemGlobbing.Internal.ILinearPattern)
    
        
    
        
        :type pattern: Microsoft.Extensions.FileSystemGlobbing.Internal.ILinearPattern
    
        
        .. code-block:: csharp
    
            public PatternContextLinearExclude(ILinearPattern pattern)
    

Methods
-------

.. dn:class:: Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinearExclude
    :noindex:
    :hidden:

    
    .. dn:method:: Microsoft.Extensions.FileSystemGlobbing.Internal.PatternContexts.PatternContextLinearExclude.Test(Microsoft.Extensions.FileSystemGlobbing.Abstractions.DirectoryInfoBase)
    
        
    
        
        :type directory: Microsoft.Extensions.FileSystemGlobbing.Abstractions.DirectoryInfoBase
        :rtype: System.Boolean
    
        
        .. code-block:: csharp
    
            public override bool Test(DirectoryInfoBase directory)
    

