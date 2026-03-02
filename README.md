# RAG Models from Scratch with Open Source
This is the repository for the LinkedIn Learning course `RAG Models from Scratch with Open Source`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

In this hands-on course, physicist and educator Alaa Moussawi guides you toward mastery of Retrieval-Augmented Generation (RAG) models. Learn to construct your own custom AI bots by integrating vector databases with language models for contextually accurate responses. Explore essential concepts such as vector embeddings, query processing, and prompt engineering. Learn how to optimize your resources by running lightweight models efficiently, even on limited hardware. Find out how to generate effective vector embeddings and extract relevant information from diverse data sources. Benefit from the flexibility of open-source software as you adapt the models to specific domains or styles, such as mimicking historical figures or aligning with specialized fields. Keep innovating and pushing boundaries with retrieval-augmented intelligence and join the vibrant open-source community in this exploratory learning adventure.

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"
