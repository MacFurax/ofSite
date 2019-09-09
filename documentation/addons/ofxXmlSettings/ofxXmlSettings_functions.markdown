#functions


<!--
_visible: True_
_advanced: False_
-->

##Description

Fill xmlSettings with content of passed parameter.
Passed parameter should be set to serialised using parameter.setSerializable(true).

If the passed parameter is a ofPrameterGroup, the group will become a parent xml element containing child parameters elements.
ofParameterGroup can be nester to build hierachical settings structure.


<!----------------------------------------------------------------------------->

###void ofDeserialize(&settings, &parameter)

<!--
_syntax: ofDeserialize(&settings, &parameter)_
_name: ofDeserialize_
_returns: void_
_returns_description: _
_parameters: const ofxXmlSettings &settings, ofAbstractParameter &parameter_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

###void ofSerialize(&settings, &parameter)

<!--
_syntax: ofSerialize(&settings, &parameter)_
_name: ofSerialize_
_returns: void_
_returns_description: _
_parameters: ofxXmlSettings &settings, const ofAbstractParameter &parameter_
_version_started: 0.10.0_
_version_deprecated: _
_summary: _
_constant: False_
_static: False_
_visible: True_
_advanced: False_
-->

_inlined_description: _







_description: _







<!----------------------------------------------------------------------------->

