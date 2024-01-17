# multi-task-learning

Dataset Link: 
https://www.kaggle.com/datasets/devalper/haber-tweetlerinin-duygu-analizi-ve-snflandrma


| Model           | Test Accuracy (Sentiment) | Test Accuracy (Topic) | Test Accuracy (MultiTask-Sentiment) | Test Accuracy (MultiTask-Topic) | Training Loss (Sentiment) | Training Loss (Topic) | Training Loss (MultiTask) | Training Duration (Sentiment) | Training Duration (Topic) | Training Duration (MultiTask) |
|-----------------|---------------------------|------------------------|--------------------------------------|-------------------------------|--------------------------|-----------------------|-----------------------------|-----------------------------|--------------------------|---------------------------|
| Tiny Bert       | 67% (8 Epoch)             | 37% (8 Epoch)          | 68%                                  | 30%                           | 0.61                     | 1.85                  | 2.47                        | 6 seconds                   | 6 seconds                | 8 seconds                   |
| Mini Bert       | 69% (8 Epoch)             | 54% (8 Epoch)          | 70%                                  | 58%                           | 0.54                     | 1.59                  | 2.09                        | 8 seconds                   | 8 seconds                | 22 seconds                  |
| Small Bert      | 88% (8 Epoch)             | 64% (8 Epoch)          | 79%                                  | 65%                           | 0.36                     | 1.18                  | 1.69                        | 8 seconds                   | 16 seconds               | 24 seconds                  |
| Medium Bert     | 85% (8 Epoch)             | 69% (8 Epoch)          | 74%                                  | 70%                           | 0.33                     | 1.06                  | 1.50                        | 24 seconds                  | 40 seconds               | 48 seconds                  |
| Base Bert       | 86% (8 Epoch)             | 74% (8 Epoch)          | 83%                                  | 75%                           | 0.20                     | 0.87                  | 1.37                        | 48 seconds                  | 72 seconds               | 136 seconds                 |
| Big Bert        | 90% (8 Epoch)             | 89% (8 Epoch)          | 89%                                  | 91%                           | 0.02                     | 0.20                  | 0.27                        | 48 seconds                  | 88 seconds               | 144 seconds                |
