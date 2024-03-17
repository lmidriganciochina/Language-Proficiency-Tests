
# Romanian, Russian, and English Proficiency Language Tests: The GAT and SHIPLEY

The Grammatical Assessment Test (GAT) was constructed following a similar methodology as in Linebarger et al., 1983, originally developed to assess comprehension failures in agrammatic aphasics (Linebarger et al., 1983). 
A new set of sentences for each of the languages (including the English version) was created, specifically designed to assess grammatical judgment and sentence comprehension of Romanian, Russian, and English (namely, 72 sentences for each language). Half of the sentences (i.e., 36) were syntactically well-formed, and 36 were systematically ill-formed - representing 12 types of grammatical rule violations. Seven of the types were violations that translated across all three language structures (Romanian, Russian, and English); whereas the other five were language-dependent. 

The English version of the Self-Administering Scale for Measuring Intellectual Impairment and Deterioration (a.k.a. Shipley Tests) was translated into Romanian and Russian. The vocabulary items were matched as closely as possible in meaning and difficulty. The normed frequency distributions of each of the items were computed in all three languages. First, word frequencies were computed from the Corpus of Contemporary American English (COCA, approximately 560,000,000 tokens) for each item in the original English test. Second, translation equivalents in Romanian and Russian (a few potential names for each item) were found. Normed frequencies were computed for each translated item in Romanian and Russian from two large corpora. Romanian item frequencies were extracted from the Balanced Corpus of Romanian Language, containing approximately 5,500,000 tokens (Ciochina et al., 2020), and in Russian, from Wikipedia text extracted from the Wiki dump, approximately 442,400,562 tokens. 

## Acknowledgements

 We would like to thank Constantin Ciochina for helping with senetence assessment, additionally, we would like to thank Victorya Boyd, Luci Sanchez, and Doina Midrigan for helping with the construction of the Romanian corpus. 
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Authors

- [@octokatherine](https://www.github.com/octokatherine)

Ludmila Midrigan-Ciochina
David P. Corina ## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |

