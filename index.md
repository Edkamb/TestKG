Welcome to the website of the Testing Knowledge Graph Applications (TestKG) Tutorial, which will be held November 2025 as part of the [ISWC'25](https://iswc2025.semanticweb.org/) conference in Nara, Japan.


## Description
Knowledge graphs (KGs) are supported by a rich and ever-growing ecosystem of standards, technologies and software tools.
For the quality of the KG application, software reliability in this ecosystem is as important as the quality and reliability of the data, in particular if KGs are used to improve confidence in an overall application, e.g., to counteract gaps.
But while the quality of the underlying software tools is critical, developers of new applications operating on KGs, as well as maintainers of legacy software have little tool and methodological support.

This tutorial aims to provide information about _automated testing_ for programs that operate on RDF and OWL inputs. It will introduce basic testing theory that describes different options to setup testing oracles and input generators, as well as describe the concrete challenges and possible solutions for KGs. The hands-on part will introduce two concrete approaches, namely mutation-based and language-based input fuzzing, to generate RDF or OWL targeting a specific application. The participants will develop two automated testing suites for a knowledge graph construction tool, and use state-of-the-art input fuzzers.

The intended learning outcomes are as follows:
* The participants will be able to select a suited black-box testing framework (input generation and testing oracle) for their specific RDF or OWL-based application.
* The participants will be able to implement a grammar-based input generator using the ISLa tool.
* The participants will be able to implement a mutation-based input generator using the RDFMutate tool.
* The participants will be able to find material and papers about other approaches to software testing.

## Venue

tba

## Material

We will publish the testing tools and material here. No preperation and no equipment beyond a laptop will needed.

## Program

### Program 02.10

| Time  | Presentation |
| -------------  | ------------- |
| --- | Slot 1 |
| 20 min | Introduction to automated testing | 
| 20 min | Setting up framework | 
| 50 min | Creating a language-based RDF-fuzzer with [ISLa](https://rindphi.github.io/isla/islaspec/) | 
| --- | Slot 2 |
| 10 min | Setting up framework | 
| 60 min | Creating a mutation-based RDF-fuzzer with [RDFMutate](https://github.com/smolang/RDFMutate) | 
| 20 min | Conclusion with pointers to further material |

## Organizers
If there are any inquiries or questions, feel free to contact the organizers:
 * [Eduard Kamburjan](mailto:eduard.kamburjan@itu.dk)
 * Einar Broch Johnsen 
 * Dominic Steinhöfel
 * Tobias John
