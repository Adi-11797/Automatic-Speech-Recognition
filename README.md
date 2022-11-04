# Automatic-Speech-Recognition
Utterance to Phoneme mapping (Time Asynchronous)

Objective: Given some speech data, we want to transcribe it into a sequence of phonemes in such a manner that it makes sense.

This is a sequence-to-sequence problem using conventional Deep Learning methodologies and Sequence models (elaborated below):
- GRU/LSTM based models on PyTorch : Baseline architecture for our problem statement (sequence-to-sequence mapping)
- Feature Extraction using CNNs (ConNeXt/ResNet) : 
- Connectionist Temporal Classification Loss : Predominant loss function in SotA for ...
- Decoders (Greedy/Beam Search decoders) 
- Levenshtein Distance



Glossary:
1) Phoneme : Distinct unit of sound in speech. The combination of these units is what we call pronunciation (Phonetic/Pronunciation of my name, ADITYA = uh-DITH-ya)
