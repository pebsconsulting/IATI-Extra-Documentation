Example Usage
~~~~~~~~~~~~~
Example ``reporting-org`` for an ``iati-organisation``.

| An example organisation ``@ref`` of *AA-AAA-123456789* is declared.
| The ``@type`` attribute declares a valid code (*40*) from the *OrganisationType* codelist.
| The optional ``@secondary-publisher`` boolean is included, for illustration.

.. literalinclude:: ../../organisation-standard-example-annotated.xml
	:language: xml
	:start-after: <!--reporting-org starts-->
	:end-before: <!--reporting-org ends-->
	:emphasize-lines: 1, 4	
	
		
Changelog
~~~~~~~~~

2.01
^^^^
Freetext is no longer allowed with this element.  It should `now be declared <http://iatistandard.org/upgrades/integer-upgrade-to-2-01/2-01-changes/#narrative-new-elements>`__  with the new child ``narrative`` element.

1.04
^^^^
| The ``@secondary-publisher`` attribute was introduced in 1.04.
