Example Usage
~~~~~~~~~~~~~
Example usage of ``transaction-type`` of ``transaction`` for an ``iati-activity``.

| The ``@code`` attribute declares a valid code (*1*) from the *TransactionType* codelist.

.. literalinclude:: ../../../activity-standard-example-annotated.xml
	:language: xml
	:start-after: <!--transaction starts-->
	:end-before: <!--transaction ends-->
	:emphasize-lines: 2

Changelog
~~~~~~~~~

2.01
^^^^
Freetext is `no longer allowed <http://iatistandard.org/upgrades/integer-upgrade-to-2-01/2-01-changes/#freetext-amended-elements>`__  within this element.
