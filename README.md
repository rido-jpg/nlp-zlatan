# WizardOfWikipedia: Knowledge-powered Conversational Agents

## Planned improvements
- [ ] find out why in certain cases source sentence is not found in training data
- [ ] try out a combination of the DM and DBOW model of Doc2Vec
- [ ] check improvements on accuracy that come from using bigger vector_size
- [ ] use a different training dataset (just the sentences used for creating wizard responses)
- [ ] use tokenizing that includes numerical data
- [ ] check if fasttext yields better performance
- [ ] train a transformer on the data

## Project implementation

~~Create a retrieval-based response Chatbot based on lecture slides 57-59 from slideset 8_chatbots~~

The *value* that our solution provides is that we have **eliminated the need of selecting a topic** in order to get fitting passages.

<p float="middle">
  <img src="https://user-images.githubusercontent.com/64151127/236822970-60d83cc4-87ad-40c8-b386-6bd63546af3d.jpg" width="45%"/>
  <img src="https://user-images.githubusercontent.com/64151127/236822989-abe3fd01-0c6b-4854-a232-d54e5e788248.jpg" width="45%"/>
</p>
TBD

## Project description

- Link to paper: https://arxiv.org/pdf/1811.01241.pdf
- Link to dataset: https://parl.ai/downloads/wizard_of_wikipedia/wizard_of_wikipedia.tgz

### Dataset

The dataset consists of open-domain dialog containing utterances that were generated from content extracted from Wikipedia articles. Multiple candidate Wikipedia passages are associated with each turn in the dialog, where one of them is considered the “reference” (i.e. correct) passage and was used to generate the response text.

### Task

The original tasks for this dataset was to (i) choose the correct passage for each turn and (ii) generate the response in the dialog using the information contained in the reference passage.

### Hints and suggestions

You could investigate one or both of the tasks described above. Moreover, you could even try to tackle the third task of retrieving the candidate set of passages for each turn in the dialog.
