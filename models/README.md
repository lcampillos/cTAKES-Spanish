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
