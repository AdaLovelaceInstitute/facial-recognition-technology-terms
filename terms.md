# Facial recognition: defining terms to clarify challenges

These four dimensions help clarify different cases of facial recognition technology, and the issues that surround them:

1.	**Task** – when people talk about facial recognition technology, they’re usually referring to the use of advanced statistical analysis to do one of a number of tasks
2.	**Data** – the data on which a facial recognition system operates
3.	**Deployment** – where and how a facial recognition technology is used in the world
4.	**Purpose** – by who, and for whom, the technology is used

### The grid:

<table>
  <tr>
    <th colspan="5">Task</th>
  </tr>
  <tr>
    <td>Detection</td>
    <td>Clustering</td>
    <td>Matching</td>
    <td>Identification</td>
    <td>Classifying</td>
  </tr>
  <tr>
    <th colspan="5">Data</td>
  </tr>
  <tr>
    <td>Personal/private vs public</td>
    <td>Retention and duration</td>
    <td>Resolution and quality</td>
    <td>Training data</td>
    <td></td>
  </tr>
  <tr>
    <th colspan="5">Deployment</td>
  </tr>
  <tr>
    <td>Live vs after-the-fact</td>
    <td>Controlled vs uncontrolled</td>
    <td>Transparency</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <th colspan="5">Purpose</td>
  </tr>
  <tr>
    <td>By who, for who?</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

## In detail:

### Task

Facial recognition technology usually refers to using advanced statistical analysis on images of people to do one (or more) of the following tasks:

* **Detection** – identifying that there is a face in an image or series of images, and where it is located in the image(s). This is usually the first step of a facial recognition process, to enable matching, identification or classification on only the relevant parts of an image.
*	**Clustering** – grouping similar faces in a collection of images. For instance, if a system had photographs of people attending a football match, clustering could be used to group together the photos of each unique face at the football match, without having pre-existing data about attendees. 
* **Matching** – comparing a facial image or images against a pre-existing set of images to see if there’s a match e.g. matching faces from shop surveillance footage against a list of images of barred persons or matching faces from a crowd against images of ‘persons of interest’ in police watchlists.
  *	**Identification** – comparing a face to a specific identity. This could be done for two purposes:
  *	**Verification** – answering the question, ‘Is this person who we think they are?’ e.g. the police checking if the person in an image matches their suspect.
*	**Authorisation** – answering the question, ‘Is this person who they claim to be?’ e.g. to allow access to something, such as using Face ID to unlock an iPhone.
*	**Classifying** – identifying a characteristic of a face, such as age, gender or expression. This is sometimes referred to as facial analysis because it’s used to tell us something about the face e.g. at a supermarket checkout to assess whether someone is old enough to buy alcohol.

### Data

*Probe images* are new, unknown images collected to input into a facial recognition system when it’s in use. Here are several ways probe images may differ across facial recognition systems:

* **Personal/private vs public** – images can be taken in public places, from government databases, from the internet, or collected privately.
*	**Retention and duration** – how long data will be stored, what format it will be stored in (e.g. original images, metadata or abstracted representation) and where it will it be stored are relevant, as are opportunities for redress and transparency about retention. 
*	**Resolution and image quality** – resolution and other quality factors such as lighting will make images more or less likely to be accurately recognised by a system. 

There are also specific considerations around **training data** – which is initial data used to develop a machine learning model for facial recognition, often referred to as ‘training’ the model. This is typically a set of images or features already labelled by a human that the model can 'learn' from. Additional considerations here include how representative the images are and the [risk of bias](http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf) – if one group of people is over/under represented in the training data, the system might be better/worse at recognising them.

### Deployment

*	**Live vs after-the-fact** – whether images are processed ‘live’, by which we mean near-real time, versus at a later point can change the way outputs can be used, and could have implication for transparency and civil liberties. For instance, ‘live’ facial recognition technology can result in actions being taken immediately, whereas performing facial recognition on historical images, such as yesterday’s CCTV, can raise questions as to whether people are aware of how their image is being processed.
*	**Controlled vs uncontrolled** – a controlled environment is one where important factors like lighting, background and position can be controlled, e.g. a lab environment, or e-passport gates where parts of the process are standardised. An uncontrolled environment is the real world, where all these things may vary, making facial recognition much more challenging.
*	**Transparency** – those deploying facial recognition technology may be more or less transparent about the fact it is being used, how it is being used and how it works. That means we may not always be able to identify the characteristics described here for every system.

### Purpose 

Lastly, it’s important to consider for and by who the technology is being used – whose purpose?

## Want to contribute?

We hope these terms are helpful for everyone - from technical experts to policymakers to the public – to be able to participate in the conversation on facial recognition. We expect them to change and improve over time, so we welcome contributions. 
