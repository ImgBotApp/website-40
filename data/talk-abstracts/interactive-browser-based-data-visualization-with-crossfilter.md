Crossfilter is a library that supports interactive exploration of large-ish, multi-dimensional data sets in the web browser. It is often used in conjunction with d3.js or another visualization library and any practitioner who is displaying and filtering data in the web browser should be aware of its capabilities. We'll cover the basics of Crossfilter, creating dimensions, aggregations, and filters in a series of basic examples. We'll also cover the processing model, going over the concept of reversible-reduce model, demonstrating the state-ful nature of Crossfilter, and explaining why this state-fulness is required for performance under interaction. Lastly, we'll discuss and show examples of more advanced approaches like custom reducers for complex aggregations.