![Scaife-Ready](https://github.com/OpenGreekAndLatin/BaseRepoForCTSCollections/workflows/Scaife-Ready/badge.svg)

# SampleRepo OGL
Sample Repo that can be forked to make it easier to create Scaife-ready collections. It is a boilerplate to start your own CTS TEI EPIDOC XML text collections, after workin in [LACE](https://github.com/brobertson/Lace2/). The important part is the [Scaife-Ready-Github Action](https://github.com/OpenGreekAndLatin/BaseRepoForCTSCollections/tree/master/.github/workflows) in the workflows folder. After forking you need to go to your Github Action tab and activate the action. That should get you started.  

If you need a more production ready workflow have a look at [OGL Latin](https://github.com/OpenGreekAndLatin/Latin/blob/master/.github/workflows/ci.yml). The workflow there will automatically generate a Github release if the [hooktest](https://github.com/Capitains/HookTest) passes (which is one of the prerequisites to have a corpus that can be displayed at the [OGL/Perseus Scaife Viewer](https://scaife.perseus.org). You can link your repo with [Zenodo](https://zenodo.org) to then procude a DOI for your corpus and make it available to the community. `.zenodo.json` file is included as an example to manage the Zenodo metadata. Change it as needed. 

I have included a CTS TEI EPIDOC XM XML files from the [Perseus Canonical Greek corpus](https://github.com/PerseusDL/canonical-greekLit), so you can see the Github Action in action. 
