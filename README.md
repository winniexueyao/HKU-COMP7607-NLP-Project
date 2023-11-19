# Metaphor Extraction With GPT-3

## Paper

[PDF](https://aclanthology.org/2023.acl-long.58/)
  
>@inproceedings{wachowiak2023metaphor,  
>  title={{Does GPT-3 Grasp Metaphors? Identifying Metaphor Mappings with Generative Language Models}},   
>  author={Wachowiak, Lennart and Gromann, Dagmar},  
>  booktitle={Proceedings of the 61th Annual Meeting of the Association for Computational Linguistics (Long Papers)},  
>  year={2023}
>}

## How to Use

- The code for repeating the experiments can be found in the notebook [analysis.ipynb](https://github.com/lwachowiak/Metaphor-Extraction-With-GPT-3/blob/main/analysis.ipynb). Used python packages are described in the [requirements file](https://github.com/lwachowiak/Metaphor-Extraction-With-GPT-3/blob/main/requirements.txt). An OpenAI API Key is required. 
- Data for prompting and fine-tuning can be found in the [Data](https://github.com/lwachowiak/Metaphor-Extraction-With-GPT-3/tree/main/Data) folder. 
- Annotations made through GPT-3 can be found in the respective folders for [validation](https://github.com/lwachowiak/Metaphor-Extraction-With-GPT-3/tree/main/Validation%20Results/Source%20Completion) and [test](https://github.com/lwachowiak/Metaphor-Extraction-With-GPT-3/tree/main/Test%20Results/Source%20Completion/Few%20Shot) results. The test data also contains the authors' annotations.

![Image](Poster-ACL.png)
