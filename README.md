# Relevanssi: add ACF subfields to index

* Contributors: cftp, hughc
* Requires at least: 3.6.1
* Tested up to: 5.1
* Stable tag: 0.3

Finds subfields from ACF and feeds them to the Relevanssi indexer so they're findable in search.

## Description

Finds subfields from ACF and feeds them to the Relevanssi indexer so they're findable in search.

To have an ACF subfield, e.g. a Repeater, indexed, do this:

1. Go to the Relevanssi options
2. Scroll to "custom fields to index"
3. Add your fields in the format `[field_name]_%_[subfield_name]`, e.g. `sections_%_section_text`
   0.3 adds support for `[field_name]_%_[subfiled_name]_%_[subfield_name]` hierarchies ie `rows_%_columns_%_content`
4. Select "Build the Index", to recreate your Relevanssi index

## Changelog

### 0.3 
* added support for multi-level hierarchical fields (ie row / fields)

### 0.2 
* BUGFIX: Fix typo in hook

### 0.1 
* First release

