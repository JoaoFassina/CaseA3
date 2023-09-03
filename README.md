# Case Telecomunicações

O nosso cliente nos trouxe um problema envolvendo a alta do churn em sua empresa.
Temos como insumo a base "churn_com_texto.csv".

Dentro do notebook Análise, temos:
- Processo de leitura e tratamento da base
- Análise exploratória
- Análises textuais
- Conclusões e sugestões

Já no notebook Modelo_QNA temos um modelo simples de perguntas e respostas cosntruído usando langchain e openAI.

E, por fim, no notebook gpt_llm_trainer_Finetune_Atentimento, originalmente disponível em https://github.com/mshumer/gpt-llm-trainer, realizamos o fine tuning do modelo Llama 2-7B-chat.
Sua execução é independente do resto e pode ser feita utilizando o free tier do Google Colab.
