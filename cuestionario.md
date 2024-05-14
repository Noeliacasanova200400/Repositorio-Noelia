<?xml version="1.0" encoding="UTF-8"?>
<!-- Thie example adapted from the PET Handbook, copyright University of Cambridge ESOL Examinations -->
<assessmentItem xmlns="http://www.imsglobal.org/xsd/imsqti_v2p2"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://www.imsglobal.org/xsd/imsqti_v2p2  http://www.imsglobal.org/xsd/qti/qtiv2p2/imsqti_v2p2p2.xsd"
	identifier="choice" title="Unattended Luggage" adaptive="false" timeDependent="false">
	<responseDeclaration identifier="RESPONSE" cardinality="single" baseType="identifier">
		<correctResponse>
			<value>A</value>
		</correctResponse>
	</responseDeclaration>
	<outcomeDeclaration identifier="SCORE" cardinality="single" baseType="float">
		<defaultValue>
			<value>0</value>
		</defaultValue>
	</outcomeDeclaration>
	<itemBody>
		<p>Look at the text in the picture.</p>
		<p>
			<img src=""C:\Users\Usuario\Downloads\descargar (2).jpg"" alt="Tarro"/>
		</p>
		<choiceInteraction responseIdentifier="RESPONSE" shuffle="false" maxChoices="1">
			<prompt>¿Mayonesa ?</prompt>
			<simpleChoice identifier="A">Siempre.</simpleChoice>
			<simpleChoice identifier="B">Nunca</simpleChoice>
			<simpleChoice identifier="C">A ratos</simpleChoice>
		</choiceInteraction>
	</itemBody>
	<responseProcessing
		template="http://www.imsglobal.org/question/qti_v2p2/rptemplates/match_correct"/>
</assessmentItem>