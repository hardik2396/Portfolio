+++
# Recent Publications widget.
# This widget displays recent publications from `content/publication/`.
widget = "publications"
active = true
date = 2016-04-20

title = "Major Project"
subtitle = ""

# Order that this section will appear in.
weight = 20

# Number of publications to list.
count = 10

# List format.
#   0 = Simple
#   1 = Detailed
#   2 = APA
#   3 = MLA
list_format = 3

# Filter by publication type.
# -1: Any
#  0: Uncategorized
#  1: Conference proceedings
#  2: Journal
#  3: Work in progress
#  4: Technical report
#  5: Book
#  6: Book chapter
publication_type = "-1"

# Exclude publications that are shown in the Selected Publications widget?
exclude_selected = false
+++
## TASK-ORIENTED LANGUAGE GROUNDING 
#### Prof.Eugenio Culurciello, Purdue University.
* Trained an agent using Asynchronous Advantage Actor-Critic (A3C) to learn task oriented language
grounding by performing specific actions in a Doom game, through natural language commands;
* Proposed an end to end neural architecture to efficiently encode the visual temporal reception of agent’s
3D environment.
* VizDoom API along with SLADE editor used to construct different environment for an agent.

## ITERATIVE ATTENTION BASED VISUAL QA
#### Prof. Gopinatha Pillai, IIT Roorkee.
* Implemented a model for Visual Question Answering(VQA) which used iterative attention mechanism
to produce a feature importance weighting vector on the VGG16 last Convolution layer features of the
image using the question embedding as a query vector.
* Final model performed better than model which exercised single pass attention mechanism. We
hypothesized that multiple steps of reasoning is required to answer questions about fine grained
information in image.

## A REVIEW ON NEURAL NETWORKS ARCHITECTURE APPLIED IN VISUAL DIALOG 
* This report proposes incorporation of attention and memory based components in basic architecture of
Visual Dialog to reduce reliance of the embedding of an entire history.
* The role of choice of memory block in RNN and word-vector is explored for improving the performance
of the model.

## OCR MODULE FOR REMITTANCE FORMS 
#### Prof. Indra Gupta, IIT Roorkee.
* Developed an end to end module using Faster RCNN in Pytorch trained on Unipen and IAM datasets;
* Developed an android demo application to post photograph to server, which is then processed by
deployed model and details populated to a database.
* Notification system is implemented by using pyfcm, python wrapper for Google’s firebase cloud messaging
service.
