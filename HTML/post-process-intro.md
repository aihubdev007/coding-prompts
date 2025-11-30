Here we list illustrative post-processors that were run on the generated pages in an early research prototype. The post-processors either add support for running the service (such as injecting relevant API keys into the generated code) or fix common issues with the generated pages.

1. Replace generated API key placeholders with actual API keys, e.g. for Google Maps.
2. Inject Javascript to detect and report client-side errors.
3. Fix Javascript errors due to model parsing issues.
4. Fix CSS errors due to missing Tailwind CSS directives.
5. Fix generated circular tailwind dependencies.
6. Ensure text characters in HTML attributes are properly escaped.
7. Remove incorrectly generated citations within Javascript code.
8. Fix common issues with APIs (e.g. maps).
9. Fix common issues with hallucinated assets (e.g. icons).
