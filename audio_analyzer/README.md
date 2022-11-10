## Cyanite Audio Analyzer

#### Contents:
1. [Overview](#overview)
2. [Quickstart Guide](#quickstart)
3. [Usage](#usage)
4. [Output Specification](#outputspec)

___
<a name="overview"></a>
### Overview:

The Cyanite Audio Analyzer extracts a variety of music-related features out of audio files using machine learning models.

An overview and explanation over the available features can be found in the [Feature Documentation](feature-documentation.md).

The audio Analyzer is optimized for CPU and GPU usage and can therefore be run on both.

___
<a name="quickstart"></a>
### Quickstart Guide:

If you want to start right away, please follow these steps:

1. Subscribe to the Audio Analyzer marketplace algorithm
2. Install and launch [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) (or comparable) on your system
3. Clone this repository and open the [example notebook](examples/cyanite-analyzer-marketplace-example.ipynb)
4. Follow the notebook instructions

___
<a name="usage"></a>
### Usage:

AWS Marketplace containers can be deployed in three ways:

| Server Mode | Payload Limit | Timeout After |
| :------------- | :------------- | :------------- |
| Real-time Inference | 6 MB | 60 seconds |
| Asynchronous Inference | 500 MB | 15 minutes |
| Batch Transformation | 100 MB | Unlimited |

__Important__:
- For real-time inference, the maximum payload size of _6MB_ is eqivalent to a 2.5min 320kbit/s MP3 or 6min 128kbit/s MP3
- For real-time inference, the 60s timeout may exceed needed processing time for longer audios using cpu-bound machines
- to circumvent these limitations, we recommend using asynchronous inference


For more information on deployment, please refer to the [Sagemaker Documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/deploy-model.html).

Calling the server is done via REST. We recommend using the [Sagemaker Python SDK](https://sagemaker.readthedocs.io) for handling invocations.

Examples for setting up and calling endpoints using the Sagemaker Python SDK can be found in the [examples](examples) section.
___
<a name="outputspec"></a>
### Output Specification:

The container returns json-formatted output.

#### JSON Schemes:
| Version | Raw Schema | Documentation | Example Output
| :--- | :--- | :--- | :--- |
| marketplace_v1 | [here](schemes/marketplace_v1/schema/marketplace_v1.schema.json) | [here](schemes/marketplace_v1/documentation/marketplace_v1.md) | [here](schemes/marketplace_v1/example/marketplace_v1_example_output.json) |
