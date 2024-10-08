# LLaVA-finetune
We are fine-tuing LLaVA 1.6 7B 

When I tried to run above LLaVA model ( https://huggingface.co/llava-hf/llava-v1.6-mistral-7b-hf)  in colab , it is showing Out of memory errors.

I got this resource from youtube.
colab file : https://colab.research.google.com/drive/10NLrfBKgt9ntPoQYQ24rEVWU-2rr1xf1#scrollTo=9ITWMKLGzhpu

LLaVA - Large Laguage and Vision Assistant

The old version is LLaVA 1.5 7B
link : llava-hf/llava-1.5-7b-hf

The latest version is LLaVA 1.6 7B  ( from HF) 
links : 1) https://huggingface.co/llava-hf/llava-v1.6-mistral-7b-hf
        2) https://huggingface.co/liuhaotian/llava-v1.6-vicuna-7b

The major difference between 1.5 and 1.6 is LLaVa-NeXT (also called LLaVa-1.6) improves upon LLaVa-1.5 by increasing the input image resolution and training on an improved visual instruction tuning dataset to improve OCR and common sense reasoning.

* I tried using Lightning AI but unable to access their studio because my email verification is pending.


My setup to fine-tune LLaVA 1.5 7B 
I used Kaggle notebooks which provide 30hr free GPU access.
STEPS:
1)open new kaggle notebook
2) set accelerator to GPU T4x2
3) load the model
4) qunatize to 4-bit
5) load the dataset
6) train the model according to the LLaVA chat template
7) load to the HF



 
