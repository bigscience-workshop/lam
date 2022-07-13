# FAQs

Below we address some questions you might have. If there is a question that isn't covered below, please feel free to ask in the [discussions](https://github.com/bigscience-workshop/lam/discussions) forum 🤗

## What is the datasets Hub?

> The Hugging Face Hub is a platform with over 50K models, 5K datasets, and 5K demos in which people can easily collaborate in their ML workflows. The Hub works as a central place where anyone can share, explore, discover, and experiment with open-source Machine Learning.

We are focusing particularly on the datasets part of the Hub which is:
> home to over 5,000 datasets in more than 100 languages that can be used for a broad range of tasks across NLP, Computer Vision, and Audio. The Hub makes it simple to find, download, and upload datasets. Datasets are accompanied by extensive documentation in the form of [Dataset Cards](https://huggingface.co/docs/hub/models-cards) and [Dataset Preview](https://huggingface.co/docs/hub/datasets-overview#datasets-on-the-hub) to let you explore the data directly in your browser. While many datasets are public, [organizations](https://huggingface.co/docs/hub/organizations) and individuals can create private datasets to comply with licensing or privacy issues. You can learn more about [Datasets here on Hugging Face Hub documentation](https://huggingface.co/docs/hub/datasets-overview).

Our goal in the hackathon is to increase the number of Library, Archive, and Museum datasets in the Hub 🚀 

## What is the datasets library?

> The [🤗 datasets](https://huggingface.co/docs/datasets/index) library allows you to programmatically interact with the datasets, so you can easily use datasets from the Hub in your projects. With a single line of code, you can access the datasets; even if they are so large they don’t fit in your computer, you can use streaming to efficiently access the data.

This means it is often possible to grab a dataset by simply calling `load_dataset` and the ID of the dataset:

```python
ds = load_dataset('blbooks')
```

We believe that the combination of the Hub and the [🤗 datasets](https://huggingface.co/docs/datasets/index) library is a powerful one for making LAM datasets more easily accessible, particularly for machine learning and other forms of computational research. 


## Are you only interested in textual data?

No, while [BigScience](https://bigscience.huggingface.co/) focuses on training large language models, the [datasets Hub](https://huggingface.co/datasets) includes tabular, image, and audio datasets. Some datasets may also include a mix of modalities. 

## What kind of license should my data have?

For this sprint, we are prioritizing data with open licenses. Many libraries, archives, and museums use [creative commons](https://creativecommons.org/) to indicate how data can be used. Most datasets using one of these licenses should be suitable for sharing. If in doubt, seek clarification in the [discussions](https://github.com/bigscience-workshop/lam/discussions) forum. 

We know some datasets can have more complicated licenses. In these cases, we will defer to the owner/custodian of the dataset to ensure we comply with license terms.

## Are you only interested in large datasets? 

While large data can be necessary for some machine learning tasks, we shouldn't only care about the quantity of data but also the qualities of this data. For example, data in languages that are not well represented in existing language datasets is very valuable. 

It can also be helpful to have data that can be used to evaluate the performance of machine learning models outside of 'traditional' benchmark datasets. This can be particularly important for applications of machine learning outside of the domains they were originally trained on. Having this evaluation data available will help assess to what extent a model trained with contemporary French data will perform well on 19th Century French text with OCR errors. 

## Do I have to own the data I'm sharing?

You don't have to own the data you want to share personally, but it should have an appropriate license that allows for it to be shared. See the license section for more discussion on this. 

## I want to upload a dataset that hasn't been previously shared. How can I do this? 

There are a few options for sharing datasets of this type. You may want to consider first making the dataset available somewhere else before submitting it as a candidate dataset. For example, you may choose to upload your dataset to a repository like [Zenodo](https://zenodo.org/) before submitting it as a candidate dataset. This will ensure you get

- a [DOI](https://en.wikipedia.org/wiki/Digital_object_identifier) for the dataset
- longer-term preservation guarantees

## Do you have some examples of LAM datasets in the Hub?
Yes, see the examples page! As the sprint progresses, you can look at the datasets being added to the [biglam organization](https://huggingface.co/biglam).

## I work for a LAM institution: can we create an organization to host our data under?

You can [create a new organization](https://huggingface.co/organizations/new) on the Hub. Once you have created a new organization, you probably want to add some colleagues. See the [docs](https://huggingface.co/docs/hub/security#access-control-in-organizations) for guidance on access controls for your organization. 

To let people know more about your organization, you may also want to write an organization card https://huggingface.co/docs/hub/org-cards#organization-cards). 

## I work for a LAM institution: we already have data hosted elsewhere. Can we still expose our data via the Hugging Face Hub?

Yes, it's possible to use a 'dataset script' to make your dataset available. This dataset script can point to the files hosted in your repository. See [guidance on creating a dataset loading script](https://github.com/bigscience-workshop/lam/wiki/contribute_data#creating-a-dataset-loading-script) for more information on doing this. 

## I am the custodian for a dataset uploaded as part of the hackathon. Can we migrate a dataset to our Hugging Face organization?

If you are the custodian of a dataset that has been added to the https://huggingface.co/biglam organization as part of the sprint and want to migrate that dataset to your organization, please open an issue on the 'community tab' for that dataset. 


## I don't know how to code; can I still contribute?

Yes! There are many valuable ways of contributing that don't require you to be able to code. For many adding many datasets, you won't need to know any Python. You may benefit from knowing some Git and being familiar with working on the command line. 

You can also make a valuable contribution by helping: 
- Identify and [suggesting potential datasets](https://github.com/bigscience-workshop/lam/wiki/contribute_data#suggesting-a-dataset)
- [Documenting datasets](https://github.com/bigscience-workshop/lam/wiki/contribute_documentation) 

## I'm a bit stuck with something; can I get some help?

Yes! We're keen that people learn something by participating as we get more data into the Hub. There are a few ways you can get help:

- If you have claimed a particular dataset and are having trouble uploading it you can tag one of the organizers in the GitHub issue for this dataset
- For more general questions you can use the [discussions](https://github.com/bigscience-workshop/lam/discussions) forum to ask for help. 

