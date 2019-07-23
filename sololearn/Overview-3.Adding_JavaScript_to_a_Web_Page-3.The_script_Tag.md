## The \<script> Tag

The \<script> tag can take two attributes, **language** and **type**, which specify the script's type:

>###### |html|  
>\<script **language**="javascript" **type**="text/javascript"><br/>
\</script>

:information_source:
The **language** attribute is deprecated, and should not be used.  

In the example below, we created an alert box inside the script tag, using the **alert()** function.  

>###### |js|
>\<html><br/>
&nbsp; &nbsp; \<head><br/>
&nbsp; &nbsp; &nbsp; \<title>\</title><br/>
&nbsp; &nbsp; &nbsp; &nbsp; \<script type="text/javascript"><br/>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; alert("This is ab alert box!");<br/>
&nbsp; &nbsp; &nbsp; &nbsp; \</script><br/>
&nbsp; &nbsp;\</head><br/>
\</html>

**Result:**

![imagem]()

:information_source:
The **type** attribute: <script type="text/javascript"> is also no longer required, as JavaScript is the default HTML scripting language.