# CatastrophicForgetting
Mitigating Catastrophic Forgetting in Medical LLMs. <br />
This project attempts to first demonstrate and then mitigate catastrophic forgetting in medical-related large language models. <br />
We go through the following steps: <br />
1. Experiment with multiple LLM's like LLAMA and Bert around the 100m to 13b parameter range <br />
2. Found Clinical-Bert (100m) achieved the best performance <br />
3. Run the base model on PubMedQA dataset <br />
4. Fine-tune on MIMIC IV dataset <br />
5. Re-test on PubMedQA dataset and compare performance <br />
6. Use elastic weight consolidation (EWC) to mitigate the effects of the catastrophic forgetting <br />

Our results found catastrophic forgetting dropped accuracy from ~74% to ~36%, however EWC was unable to successfully mitigate the effects. <br />
Link to the full paper here: https://acrobat.adobe.com/id/urn:aaid:sc:VA6C2:5e77abae-12ee-43e9-8a91-8d60197b777a
