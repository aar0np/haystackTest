# haystackTest

A short Python script which tests the Astra DB integration found in Haystack's documentation: [Haystack's Astra DB document store integration](https://docs.haystack.deepset.ai/v2.0/docs/astradocumentstore)

## requirements

Set the following environment variables:
```
export ASTRA_DB_APP_TOKEN=AstraCS:abcdefNOTREALghijk:lmnopqrsBLAHBLAHBLAHtuvwxyz
export ASTRA_DB_API_ENDPOINT=https://b9aff773-also-not-real.apps.astra.datastax.com
```

Install the following libraries:
```
pip install haystack-ai
pip install astra-haystack
```

Make sure that the following Python library versions are installed:
```
pip3 freeze | grep haystack
astra-haystack==0.4.1
haystack==0.42
haystack-ai==2.0.0b7
haystack-bm25==1.0.2
```

## Execution
```
python haystack_test.py
```