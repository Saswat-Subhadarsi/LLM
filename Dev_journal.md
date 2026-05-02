# Overview

This is my personal dev journal of what knowledge I acquired throughout my journey of building this LLM

## DAY 1

Basics and what to do.

## DAY 2

Had a very hectic day still made some time for learning. Learned basics and pretraining and finetuning, moved to simplified transformer architecture.
Went a bit into attention mechanisms. Read about BERT and GPT just the overview nothing much. 
Moving pretty slowly I think. Better than nothing. Lets see where it goes.

## DAY 3

Stage of making a llm
Auto regression
emergent behaviour

## DAY 4

Stage 1 starts
Building a tokenizer
Learning basic tokenizer about special tokens and token ids.

## DAY 5

Dove deep into Byte Pair Encoding
Read the paper ```Neural Machine Translation of Rare Words with Subword Units``` paper for 
reference of Byte Pair Encoding

## DAY 6 

Finally made all the functions and made base training loop. 
Found so many edge cases to look out for.
Thought of some features to add and make the model more robust.
Todo : Need to make it more practical and fast.

## DAY 7

Found a huge bug in my training loop's merge function
Now I am training my BPE on 231k vocab freq
Pretty excited
The BPE is quite in efficient so I need to make optimizations

## DAY 8

My BPE trainer is taking forever to train 30k merges so I need to optimize it I guess
Basically performed and recorded some practicals today

## DAY 9

Performed major optimizations on my Training loops
Mainted a global access data in the Train class so that recreation of it does not occur every iteration
