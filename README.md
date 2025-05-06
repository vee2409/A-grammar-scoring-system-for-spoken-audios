# A-grammar-scoring-system-for-spoken-audios
This presents a grammar scoring engine tailored for spoken language data, built using a two-model ensemble approach. 
 I utilized OpenAI's Whisper for audio transcription and extracted deep semantic representations using both RoBERTa and Sentence-BERT (SBERT) embeddings. These were enriched with handcrafted grammatical features such as part-of-speech counts and word statistics. The combined feature set was used to train a LightGBM regressor to predict grammar scores on a scale from 1 to 5.
