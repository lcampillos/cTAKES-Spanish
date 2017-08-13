# cTAKES-Spanish

Models and tools for using cTAKES with Spanish texts.

To be used with cTAKES 4.0.0 (the version as of August 2017)

## models
Includes POS models trained on Apache OpenNLP (vs. 1.7.2).

Annotated texts come from [this repository](https://github.com/utcompling/OpenNLP-Models/tree/master/lang/es/pos/data/pos-es)

Declare the POS model at `ctakes-4.0.0/desc/ctakes-pos-tagger/desc/POSTagger.xml`:

`<nameValuePair>`

`<name>PosModelFile</name>`

`<value>`

`<string>org/apache/ctakes/postagger/models/es-maxent-model-1-7.bin</string>`

`</value>`

`</nameValuePair>`

Place the model at `ctakes-4.0.0/resources/org/apache/ctakes/postagger/models/`

## lib
Includes the file `ctakes-gui-4.0.0.jar` for the cTAKES Dictionary Creator adapted to extract a customized dictionary of Spanish terms from the UMLS.

Note that you need to download and build the UMLS Metathesaurus locally for creating a customized dictionary.
