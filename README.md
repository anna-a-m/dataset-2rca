# 2RCa - Russian Conversational Context Rewrite dataset

This dataset ia based on the TolokaPersonaChatDataset (available at https://toloka.ai/datasets/). 2RCa aims at providing data on ellipsis and anaphora resolved rewrites from daily coversations in Russian. Total length in dialogues is **1048**, total length in turns is **5541**.

Example of data:

```
   {
    'History': [
        'Привет.',
        'Привет.',
        'Как дела?) Работаешь?)',
        'Работаю программистом, мечтаю выпустить сборник. А ты кем работаешь?'
        ],
    'Dia_ID_hash': 'dia_f587df49',
    'Utt_ID_hash': 'utt_7132ac50',
    'Phrase': 'Сборник программ? А я работаю продавцом. И мой муж продавец.',
    'Rewrite': 'Ты мечтаешь выпустить сборник программ? А я работаю продавцом. И мой муж продавец.'
   }
```
