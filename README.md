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

<table>
  <tr>
    <th>Authors</th><th colspan="1">Within-World</th><th colspan="1">Across-World</th>
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

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/igorlabutov/textworldsqa.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
