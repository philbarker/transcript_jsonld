Attempts at creating JSON-LD from a JSON representation of a PESC Transcript.

Work in progress. Not endorsed. Do not re-use without permission.

You can [view the work in progress](https://tinyurl.com/ydocp59a) using the JSON-LD playground.

## Outline
CollegeTranscriptInstanceRevised.json is example data in json

 context.json is an attempt at a context block to map the keys in the example to RDF (mostly CTDL)

 TransmissionData-ld_inlineContext.json and  TransmissionData-ld_inlineContext.json include the context at the top of the example data (inline and linked).

 ctdlBasedContext.json is a simple context that can be used to reframe the JSON-LD example data against the CTDL context. This has the effect of producing more readable JSON-LD, with prefixes for the keys rather than full URIs.
