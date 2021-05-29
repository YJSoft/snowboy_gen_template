# Snowboy pmdl create template
Easy to use snowboy create repo.

# How to use
1. Create repo based on this repo(Use "Use this template" button)
2. Upload `record1.wav`, `record2.wav`, `record3.wav` files in source folder(Use Add file-Upload files or git client to upload wav file)
3. Workflow will run(You can cancel first workflow run since that will be useless)
4. Download artifact `pmdl` when workflow run is finished

# Notice
This will stop working when github removes ubuntu-16.04 from actions. there are no alternative since module file(`_snowboy.so`) only supports Ubuntu 16.04.

# Copyright notice
This repo uses script from https://github.com/seasalt-ai/snowboy/blob/master/Dockerfile 
