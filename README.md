Attempts at creating JSON-LD from a JSON representation of a PESC Transcript.

Work in progress. Not endorsed. Do not re-use without permission.

You can [view the work in progress](https://tinyurl.com/ydocp59a) using the JSON-LD playground.

## Outline
CollegeTranscriptInstanceRevised.json is example data in json, automatically converted from XML

CollegeTranscriptInstanceRevisedLD_inlineContext.json is the same example data but in json, but as JSON-LD and recast to the schema described in the TAP+SHACL directory. This is the main file used for development.

context.json is a context block generated from tabular application profile in the TAP+SHACL directory, and CollegeTranscriptInstanceRevisedLD_remoteContext.json is the JSON block + a remote reference to this. These files are often some revisions behind the _inlineContext file.

TAP+SHACL directory contains the schema described in graphical format, as a Tabular Application Profile (TAP),  and in SHACL derived from the TAP.

Examples directory contains small proof of concept examples, mostly dated.

Archive directory contains false starts and other bits and bobs.
