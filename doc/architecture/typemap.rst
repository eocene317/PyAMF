************
  Type Map 
************


.. topic:: Introduction

   The following is a guide to the ActionScript to Python type
   mappings.


Basic Types
===========

The following types are available in Adobe Flash Player 6 and newer:

+-------------------------------------+---------------------------------+
| ActionScript Type                   | Python Type	                |
+=====================================+=================================+
| ``null``          		      | ``None``    	                |
+-------------------------------------+---------------------------------+
| ``undefined``, ``void``             | ``pyamf.Undefined``             |
+-------------------------------------+---------------------------------+
| ``String``     	              | ``unicode``                     |
+-------------------------------------+---------------------------------+
| ``Boolean``                         | ``bool``                        |
+-------------------------------------+---------------------------------+
| ``Number``     		      | ``float``                       |
+-------------------------------------+---------------------------------+
| ``Date``                            | ``datetime.datetime``           |
+-------------------------------------+---------------------------------+
| ``XML``                             | ``ElementTree.Element``         |
+-------------------------------------+---------------------------------+
| ``Array``               	      | ``list, tuple``                 |
+-------------------------------------+---------------------------------+
| ``Object``    		      |	``dict``		        |
+-------------------------------------+---------------------------------+
| ``RecordSet``                	      | ``pyamf.amf0.RecordSet``        |
+-------------------------------------+---------------------------------+
| Typed Object (other than the above) | class instance (registered via  |
|				      | ``pyamf.register_class``)       |
+-------------------------------------+---------------------------------+


AMF3
====

The following types are available in the Adobe Flash Player 9 and newer:

+-------------------------------------+---------------------------------+
| ActionScript Type                   | Python Type	                |
+=====================================+=================================+
| ``int``, ``uint``          	      | ``int``    	                |
+-------------------------------------+---------------------------------+
| ``ByteArray``             	      | ``pyamf.amf3.ByteArray``        |
+-------------------------------------+---------------------------------+
| ``DataInput``     	              | ``pyamf.amf3.DataInput``        |
+-------------------------------------+---------------------------------+
| ``DataOutput``                      | ``pyamf.amf3.DataOutput``       |
+-------------------------------------+---------------------------------+


Flex (AMF3)
===========

The following types are available in `Adobe Flex 2
<http://opensource.adobe.com/wiki/display/flexsdk/>`_ and newer:

+-------------------------------------+---------------------------------------------+
| ActionScript Type                   | Python Type	                            |
+=====================================+=============================================+
| ``ObjectProxy``          	      | ``pyamf.flex.ObjectProxy``                  |
+-------------------------------------+---------------------------------------------+
| ``ArrayCollection``         	      | ``pyamf.flex.ArrayCollection``              |
+-------------------------------------+---------------------------------------------+
| ``AbstractMessage``     	      | ``pyamf.flex.messaging.AbstractMessage``    |
+-------------------------------------+---------------------------------------------+
| ``AcknowledgeMessage``              | ``pyamf.flex.messaging.AcknowledgeMessage`` |
+-------------------------------------+---------------------------------------------+
| ``AsyncMessage``                    | ``pyamf.flex.messaging.AsyncMessage``       |
+-------------------------------------+---------------------------------------------+
| ``CommandMessage``                  | ``pyamf.flex.messaging.CommandMessage``     |
+-------------------------------------+---------------------------------------------+
| ``ErrorMessage``                    | ``pyamf.flex.messaging.ErrorMessage``       |
+-------------------------------------+---------------------------------------------+
| ``RemotingMessage``                 | ``pyamf.flex.messaging.RemotingMessage``    |
+-------------------------------------+---------------------------------------------+
| ``DataMessage``                     | ``pyamf.flex.data.DataMessage``             |
+-------------------------------------+---------------------------------------------+
| ``SequencedMessage``                | ``pyamf.flex.data.SequencedMessage``        |
+-------------------------------------+---------------------------------------------+
| ``PagedMessage``                    | ``pyamf.flex.data.PagedMessage``            |
+-------------------------------------+---------------------------------------------+
| ``DataErrorMessage``                | ``pyamf.flex.data.DataErrorMessage``        |
+-------------------------------------+---------------------------------------------+