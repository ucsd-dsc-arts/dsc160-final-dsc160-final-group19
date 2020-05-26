# Project Title

DSC160 Data Science and the Arts - Final Project - Generative Arts - Spring 2020

Project Team Members: 
- Nikolas Racelis-Russell, nracelis@ucsd.edu
- Iakov Vasilyev, ivasilie@ucsd.edu
- Cameron Shaw, c8shaw@ucsd.edu

## Abstract

  Generative music is not a new idea, and has been around as early as 1989. However, the use of neural networks for this creation has not been popularized until recently (Yang et al., 2017). This project plans to use neural networks to generate music from MIDI jazz files. However this presents many challenges, as melody can be generated, but structure is much harder to generate due to variance. We propose to compose music using LSTMs to attempt to generate melody from MIDI files scraped off the internet.
  
  In addition to researching LSTMs,  we found that different types of neural network tools are useful for specific tasks. For example, HyperGAN is fast and good at intervals but can often be unspecific about the note played and does not have a good understanding of “directions,” meaning it would not pay attention to the more established tonal progressions such as the circle of fifths. Meanwhile, PixelCNN is very slow but has no problem with direction meaning it would stick to more established musical tropes, which is (from personal musical experience) probably the most important part in creating a catchy, human-like composition.
  
  The form we want to present our project in is a progression of how the model has trained, meaning presenting samples of the music at certain epochs. There is a lot of flexibility in where we could potentially take the analysis, but the overall idea is to generate music good enough to trick listeners. We would ask people to determine which composition was computer-generated, and expect them to be fooled around 25% of the time like the DeepBach research.
  
  Right now even the best computer-generated music is not good enough to be considered an actual source of entertainment, and the examples that come close are usually heavily stylized compositions. In the future, however, there is a chance that machine-produced entertainment will rival that of human origins, and we would like to see how close we can get to that point with the current algorithms and levels of technology.

__References and Inspirations:__
- __MidiNET, CNN-GAN__: https://opus.lib.uts.edu.au/bitstream/10453/6862/1/2004001187.pdf
- __Combining theory between RNN and LSTM__: http://cs229.stanford.edu/proj2016/report/Lou-MusicGenerationUsingNeuralNetworks-report.pdf
- __Easy to understand example__: https://medium.com/@leesurkis/how-to-generate-techno-music-using-deep-learning-17c06910e1b3
- __Videogame music with one instrument (lots of music theory)__: https://www.youtube.com/watch?v=UWxfnNXlVy8&feature=youtu.be
- __DeepMusic__: https://github.com/llSourcell/How_to_generate_music_in_tensorflow_LIVE
- __DeepBach__: https://arxiv.org/abs/1612.01010

## Data and Model

(10 points) 

In the final submission, this section will describe both the data you use for this project and any pre-existing models/neural nets. For each you should provide the name, a textual description, and a link. If there is a paper (for neural net) link that as well.
- Such and such Neural Net. The short description of this neural net. 
  - [link to code]().
  - [Title of Paper with Link](). 
- Training data. Short description of training data including bibliographic info. [link to data]().

## Code

(20 points)

This section will link to the various code for your project (stored within this repository). Your code should be executable on datahub, should we choose to replicate your result. This includes code for: 

- code for data acquisition/scraping
- code for preprocessing
- training code (if appropriate)
- generative methods

Link each of these items to your .ipynb or .py files within this seection, and provide a brief explanation of what the code does. Reading this section we should have a sense of how to run your code.

## Results

(30 points) 

This section should summarize your results and will embed links to documentation to significant outputs. This should document both process and show artistic results. This can include figures, sound files, videos, bitmaps, as appropriate to your generative art idea. Each result should include a brief textual description, and all should be listed below: 

- image files (`.jpg`, `.png` or whatever else is appropriate)
- audio files (`.wav`, `.mp3`)
- written text as `.pdf`

## Discussion

(30 points, three to five paragraphs)

The first paragraph should be a short summary describing your results.

The subsequent paragraphs could address questions including:
- Why is this culturally innovative?
- How does your generative computational approach differ from traditional art/music/cultural production? 
- How do your results relate to broader social, cultural, economic political, etc., issues? 
- What are the ethical concerns for this form of generative art? 
- In what future directions could you expand this work?

## Team Roles

Provide an account of individual members and their efforts/contributions to the specific tasks you accomplished.

## Technical Notes and Dependencies

Any implementation details or notes we need to repeat your work. 
- Additional libraries you are using for this project
- Does this code require other pip packages, software, etc?
- Does this code need to run on some other (non-datahub) platform? (CoLab, etc.)

## Reference

All references to papers, techniques, previous work, repositories you used should be collected at the bottom:
- Papers
- Repositories
- Blog posts
