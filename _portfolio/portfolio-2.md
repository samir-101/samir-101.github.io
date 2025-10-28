---
title: "Rabindra-GPT"
excerpt: "A GPT-2 based transformer model for generating Bengali text trained on the essays of Rabindra Nath Tagore <br/>"
collection: portfolio
---

An experimental GPT-2 Model clone trained on Rabindranath Tagore's Essay works dataset. The code is mostly based on Andrej Karpathy's [Building GPT From Scratch](https://github.com/karpathy/ng-video-lecture) series and the dataset is derived from [Kaggle](https://www.kaggle.com/code/sayankr007/bengali-text-generation-and-language-modelling/).

Currently, the model is trained on a small dataset of 100 essays and generates text in Bengali. The model can be further fine-tuned and improved with a larger dataset and more training. Tokenization is done using Byte Pair Embedding algorithm from `tiktoken` library and the model is trained using PyTorch.

**Example Token Input and Output:**  
কত অধ্যবসায় কত ভীষণ কতই চক্ষুবদ্ধ -  
কত অধ্যবসায় কত ভীষণ কতই চক্ষুবদ্ধ বৃষের অনুবর্তন করা তেতো আনা সহজ হয় খাটিয়েছেন তবু শ্রোতাদের নাই । এঁদের শিক্ষিত ছেলের বড়ো জটিলতায় যার নহেন । এ দেশে আধুনিক রসায়ন ভ্রাতৃসংঘের ইংরেজি ভাষা সমাজে কাড়াকাড়ি সাধনে স্বতন্ত্র চিরস্মরণীয় করে বেড়াচ্ছেন । এসেছিল ধর্মানুষ্ঠানেরই অন্তর্গত । দেশের যুদ্ধের সময় এখানকার উত্তরতম জটিলতার আভাস জ্ঞানম্ কলাপাতায় আমাদের দেশের জীবনের লক্ষণ যত দিন নেই তত উৎকল দত্তের অধিকারীর এবং ঘোষিত সেখানে অস্পষ্ট । ইন্সিওরেন্সের আট বছরের মধ্যে জাপানে এসেছে ছেলেরা বিচিত্র নিবেদিত । মধ্যযুগে প্রত্যহ যদিচ চাষীদের সঙ্গে দূরের ইস্কুল থামিয়াছে এক দিকে রূপ সেখানেও আমাদের একেবারে নবীন জিনিসকে সংগ্রহ করতে পারে না । আমাদের দেশের অনেক বড়ো বড়ো