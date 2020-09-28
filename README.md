# NER-model

- This Repo contains coupns.csv, word.txt and jupyter notebook.
- Assignment includes two tasks : - 1). Extract FaceValue from OfferDetails - 2). Extract Products from OfferDetails

### Task-1
- Here, we can extract FaceValue from OfferDetails using Regex function.

### Task-2
- To solve task-2, we need to build NER model which assigns P label to Product names and O label to Others.
- The labels are assigned manually as we have only OfferDetails data.
- Using LSTMs and BiLSTMs we build the many to many architecture which takes OfferDetails as an input and Lables (P/O) as an output.

More details related to the model are added in Jupyter notebook itself.
