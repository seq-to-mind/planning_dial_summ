1. We use the # as the utterance segmentation token. You can replace it with other special tokens such as [SEP].  

2. Source content and reference summary are in two files. For instance, the `text_train.source` contains the input dialogue samples of training set, and their reference summaries are in the file `train.target`.  

3. The controllable information for training and evaluation is at the beginning of each dialogue sample. For instance, for the first sample in training set `{ Amanda | Jerry }  # Amanda: I baked  cookies. Do you want some? # Jerry: Sure! # Amanda: I'll bring you tomorrow :-)`, the entity-based occurrence planning is `{ Amanda | Jerry }`.

