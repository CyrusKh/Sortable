# Sortable
From their website:

Background

At Sortable we do a lot of data integration. A simplified example: product specifications might come from one data source, product pricing from another, and product reviews from a third. A major challenge in working with all this data is determining when two pieces of information from disparate data sources are actually talking about the same product. In academic circles this problem is sometimes called Record Linkage, Entity Resolution, Reference Reconciliation, or a host of other fancy terms. We describe this problem very technically as “matching.”

The Challenge

The goal is to match product listings from a 3rd party retailer, e.g. “Nikon D90 12.3MP Digital SLR Camera (Body Only)” against a set of known products, e.g. “Nikon D90”.

We’ll provide you with a set of products and a set of price listings matching some of those products. The task is to match each listing to the correct product. Precision is critical. We much prefer missed matches (lower recall) over incorrect matches, so try hard to avoid false positives. A single price listing may match at most one product.
