## TextWorlds QA

TextWorlds QA is a new Question Answering dataset introduced in the [following paper](PersonalNarrativeQA.pdf). The inspiration behind the creation of this dataset is the vision that our future personal assistants will be able to learn new knowledge from explicit verbal instruction, and then answer questions over that knowledge. 

A quick summary of what this dataset is about (from the paper):

We synthesize narratives in five diverse worlds, each containing a thousand narratives and where each narrative describes the evolution of a simulated user's world from a first-person perspective. In each narrative, the simulated user may introduce new knowledge, update existing knowledge or express a state change (e.g., *"Homework 3 is now due on Friday"* or *"Samantha passed her thesis defense"*). Each narrative is interleaved with questions about the current state of the world, and questions range in complexity depending on the amount of knowledge that needs to be integrated to answer them. This allows us to benchmark a range of QA models at their ability to answer questions that require different extents of relational reasoning to be answered.

### Download 

You can download the dataset [here](https://conversationalmlcourse.bitbucket.io/datasets/stories_dataset.tar.gz).

### Attribution

If you use the dataset please cite:

Labutov, Igor, Bishan Yang, Anusha Prakash, Amos Azaria. "Multi-Relational Question Answering from Narratives: Machine Reading and Reasoning in Simulated Worlds" Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics.

### Benchmarks 

Please email us directly to report new results on this dataset. We will maintain the list of publications that report performance on this data, and report these benchmarks in the table below:

<table>
  <tr>
    <th>Model</th><th colspan="1">Within-World</th><th colspan="1">Across-World</th>
  </tr>
  <tr>
    <th></th>
    <th><i>F1</i></th>
    <th><i>F1</i></th>
  </tr>  
  <tr>
    <td>MemN2N</td>
    <td>57.0</td>
    <td>9.2</td>
  </tr>
  <tr>
    <td>BIDAF</td>
    <td>72.8</td>
    <td>16.6</td>
  </tr>
  <tr>
    <td>DrQA</td>
    <td>79.4</td>
    <td>23.9</td>
  </tr>
</table>

### Contact

If you find any issues with the dataset, or if you would like to report new results and be added to the benchmark list, please [contact us](igor.labutov@laer.ai).
